---
title: "LoadOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供文档加载的选项。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

提供文档加载的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 要加载的文件类型。 |
| [getExtension()](#getExtension--) | 要初始化的文件扩展名。 |
| [getPassword()](#getPassword--) | 打开受密码保护的文件的密码。 |
| [getEncoding()](#getEncoding--) | 打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。 |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |
| encoding | java.nio.charset.Charset | 打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。 |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |
| encoding | java.nio.charset.Charset | 打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。 |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 扩展名 | java.lang.String | 要加载的文件扩展名。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |
| encoding | java.nio.charset.Charset | 打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。 |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要初始化的文件类型。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |
| encoding | java.nio.charset.Charset | 打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。 |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要初始化的文件类型。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |
| 密码 | java.lang.String | 打开受密码保护的文件的密码。 |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


初始化 [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要初始化的文件类型。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要加载的文件类型。 |

### getType() {#getType--}
```
public final FileType getType()
```


要加载的文件类型。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


要初始化的文件扩展名。

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


打开受密码保护的文件的密码。

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


打开基于文本的文件（例如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）时使用的编码。默认值为 System.Text.Encoding.Default (java.nio.charset.Charset)。

**Returns:**
java.nio.charset.Charset
