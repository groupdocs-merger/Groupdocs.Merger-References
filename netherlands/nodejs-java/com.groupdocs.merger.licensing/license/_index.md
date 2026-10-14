---
title: "Licentie"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt methoden om het component te licentiëren."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Biedt methoden om de component te licentiëren. Meer informatie over licenties vind je [hier][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [License()](#License--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licentieert de component. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licentieert de component. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licentieert de component.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseStream | java.io.InputStream | De licentiestroom. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licentieert de component.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licensePath | java.lang.String | Het licentiepad. |

