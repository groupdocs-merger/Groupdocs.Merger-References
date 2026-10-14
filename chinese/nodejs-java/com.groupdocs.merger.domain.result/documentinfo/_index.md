---
title: "DocumentInfo"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "定义文档描述属性。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

定义文档描述属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | 初始化 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 类的新实例。 |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | 初始化 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 类的新实例。 |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | 初始化 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getIndex()](#getIndex--) | 文档索引。 |
| [getStream()](#getStream--) | 文档流。 |
| [getPassword()](#getPassword--) | 文档密码。 |
| [getType()](#getType--) | 获取文件类型。 |
| [getPages()](#getPages--) | 定义文档页面集合。 |
| [getPageCount()](#getPageCount--) | 文档页面计数。 |
| [getSize()](#getSize--) | 文档大小（字节） |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


初始化 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |
| 流 | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 文件的类型。 |
| 密码 | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


初始化 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int |  |
| 流 | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 文件的类型。 |
| 密码 | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 要查看的页面列表。 |
| 大小 | long | 文件的大小。 |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


初始化 [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 文件的类型。 |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 要查看的页面列表。 |
| 大小 | long | 文件的大小。 |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


文档索引。

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


文档流。

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


文档密码。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


获取文件类型。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


定义文档页面集合。

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


文档页面计数。

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


文档大小（字节）

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
