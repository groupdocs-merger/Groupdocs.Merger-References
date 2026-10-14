---
title: "许可证"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供用于授权组件的方法。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

提供对组件进行授权的方法。了解更多授权信息，请点击[此处][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [License()](#License--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | 授权组件。 |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | 授权组件。 |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


授权组件。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseStream | java.io.InputStream | 许可证流。 |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


授权组件。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licensePath | java.lang.String | 许可证路径。 |

