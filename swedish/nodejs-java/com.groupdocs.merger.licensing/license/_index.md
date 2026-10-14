---
title: "Licens"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller metoder för att licensiera komponenten."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Tillhandahåller metoder för att licensiera komponenten. Läs mer om licensiering [här][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Licensierar komponenten. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Licensierar komponenten.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Licensströmmen. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Licensierar komponenten.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licensePath | java.lang.String | Licenssökvägen. |

