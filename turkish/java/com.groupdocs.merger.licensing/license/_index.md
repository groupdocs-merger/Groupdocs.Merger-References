---
title: "Lisans"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Bileşeni lisanslamak için yöntemler sağlar."
type: docs
weight: 10
url: /tr/java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Bileşeni lisanslamak için yöntemler sağlar. Lisanslama hakkında daha fazla bilgiyi [burada][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [License()](#License--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Bileşeni lisanslar. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Bileşeni lisanslar. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Bileşeni lisanslar.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Lisans akışı. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Bileşeni lisanslar.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licensePath | java.lang.String | Lisans yolu. |

