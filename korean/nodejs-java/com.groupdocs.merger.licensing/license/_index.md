---
title: "라이선스"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "구성 요소에 라이선스를 적용하는 메서드를 제공합니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

구성 요소에 라이선스를 적용하는 메서드를 제공합니다. 라이선스에 대해 자세히 알아보려면 [여기][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


구성 요소에 라이선스를 적용합니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licenseStream | java.io.InputStream | 라이선스 스트림. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


구성 요소에 라이선스를 적용합니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| licensePath | java.lang.String | 라이선스 경로. |

