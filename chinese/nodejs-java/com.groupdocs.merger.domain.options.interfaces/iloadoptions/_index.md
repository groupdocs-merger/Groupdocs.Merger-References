---
title: "ILoadOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于文档加载选项的接口。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

用于文档加载选项的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 要打开的文件类型。 |
| [getPassword()](#getPassword--) | 打开受密码保护的文件的密码。 |
| [getExtension()](#getExtension--) | 要打开的文件扩展名。 |
| [getEncoding()](#getEncoding--) | 打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。 |
### getType() {#getType--}
```
public abstract FileType getType()
```


要打开的文件类型。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


打开受密码保护的文件的密码。

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


要打开的文件扩展名。

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


打开基于文本的文件（如 [FileType.CSV](../../com.groupdocs.merger.domain/filetype\\#CSV) 或 [FileType.TXT](../../com.groupdocs.merger.domain/filetype\\#TXT)）时使用的编码。默认值为 [DefaultCharset][]。


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
