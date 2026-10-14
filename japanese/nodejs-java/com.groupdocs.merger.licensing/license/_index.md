---
title: "ライセンス"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "コンポーネントをライセンスするためのメソッドを提供します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.merger.licensing/license/
---
**Inheritance:**
java.lang.Object
```
public final class License
```

コンポーネントにライセンスを付与するメソッドを提供します。ライセンスに関する詳細は[こちら][].


[here]: https://purchase.groupdocs.com/faqs/licensing
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
### License() {#License--}
```
public License()
```


### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


コンポーネントにライセンスを付与します。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licenseStream | java.io.InputStream | ライセンスストリームです。 |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


コンポーネントにライセンスを付与します。

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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| licensePath | java.lang.String | ライセンスパスです。 |

