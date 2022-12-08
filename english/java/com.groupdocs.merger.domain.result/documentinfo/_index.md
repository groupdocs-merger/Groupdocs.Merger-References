---
title: DocumentInfo
second_title: GroupDocs.Signature for Java API Reference
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
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initializes new instance of [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets the file type. |
| [getPages()](#getPages--) | Defines document pages collection. |
| [getPageCount()](#getPageCount--) | The document pages count. |
| [getSize()](#getSize--) | Document size in bytes |
| [toString()](#toString--) | Returns a string that represents the current object. |
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
