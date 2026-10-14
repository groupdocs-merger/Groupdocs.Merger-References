---
title: "License"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει μεθόδους για την αδειοδότηση του στοιχείου."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Παρέχει μεθόδους για την άδεια του στοιχείου. Μάθετε περισσότερα για την αδειοδότηση [εδώ][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [License()](#License--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Αδειοδοτεί το στοιχείο. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Αδειοδοτεί το στοιχείο. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Αδειοδοτεί το στοιχείο.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing Stream of the license file.
>  
>  using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
>  {
>      GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
>      lic.SetLicense(licenseStream);
>  }
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Η ροή άδειας. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Αδειοδοτεί το στοιχείο.

--------------------

> ```
> The following example demonstrates how to set a license
>  passing a path to the license file.
>  
>  string licensePath = "GroupDocs.Merger.lic";
>  GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
>  lic.SetLicense(licensePath);
> ```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licensePath | java.lang.String | Η διαδρομή άδειας. |

