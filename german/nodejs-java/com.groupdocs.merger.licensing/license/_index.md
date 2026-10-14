---
title: "Lizenz"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Stellt Methoden bereit, um die Komponente zu lizenzieren."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Stellt Methoden bereit, um die Komponente zu lizenzieren. Erfahren Sie mehr über Lizenzierung [hier][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Lizenziert die Komponente. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Lizenziert die Komponente. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Lizenziert die Komponente.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Der Lizenzstream. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Lizenziert die Komponente.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licensePath | java.lang.String | Der Lizenzpfad. |

