---
title: "Lisensi"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Menyediakan metode untuk melisensikan komponen."
type: docs
weight: 10
url: /id/java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

Menyediakan metode untuk melisensikan komponen. Pelajari lebih lanjut tentang pelisensian [here][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [License()](#License--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Melisensikan komponen. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Melisensikan komponen. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Melisensikan komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Aliran lisensi. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Melisensikan komponen.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licensePath | java.lang.String | Jalur lisensi. |

