---
title: DocumentInfo
second_title: GroupDocs.Merger for Java API Reference
description: Defines document description properties.
type: docs
weight: 10
url: /java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Defines document description properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class. |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class. |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getIndex()](#getIndex--) | The document index. |
| [getStream()](#getStream--) | The document stream. |
| [getPassword()](#getPassword--) | The document password. |
| [getType()](#getType--) | Gets the file type. |
| [getPages()](#getPages--) | Defines document pages collection. |
| [getPageCount()](#getPageCount--) | The document pages count. |
| [getSize()](#getSize--) | Document size in bytes |
| [toString()](#toString--) | Returns a string that represents the current object. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file. |
| password | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file. |
| password | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | The list of pages to view. |
| size | long | The size of the file. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | The list of pages to view. |
| size | long | The size of the file. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


The document index.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


The document stream.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


The document password.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Gets the file type.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Defines document pages collection.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


The document pages count.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Document size in bytes

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
