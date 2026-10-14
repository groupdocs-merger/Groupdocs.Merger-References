---
title: "IImportDocumentOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于导入嵌入式文档的接口。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

用于导入嵌入式文档的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 嵌入对象的数据。 |
| [getExtension()](#getExtension--) | 嵌入对象的扩展名。 |
| [getPageNumber()](#getPageNumber--) | 嵌入对象插入的页码。 |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


嵌入对象的数据。

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


嵌入对象的扩展名。

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


嵌入对象插入的页码。

**Returns:**
int
