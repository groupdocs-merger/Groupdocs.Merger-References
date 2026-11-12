---
title: "رخصة"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر طرقًا لتفعيل المكوّن."
type: docs
weight: 10
url: /ar/java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

يوفر طرقًا لترخيص المكوّن. تعلّم المزيد عن الترخيص [هنا][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [License()](#License--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | يرخص المكوّن. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | يرخص المكوّن. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


يرخص المكوّن.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| licenseStream | java.io.InputStream | دفق الترخيص. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


يرخص المكوّن.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| licensePath | java.lang.String | مسار الترخيص. |

