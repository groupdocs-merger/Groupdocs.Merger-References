---
title: IDocumentInfo
second_title: GroupDocs.Merger for Java API Reference
description: Interface for the document description properties.
type: docs
weight: 12
url: /java/com.groupdocs.merger.domain.result/idocumentinfo/
---```
public interface IDocumentInfo
```

Interface for the document description properties.
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets the file type. |
| [getPages()](#getPages--) | Defines document pages collection. |
| [getPageCount()](#getPageCount--) | The document pages count. |
| [getSize()](#getSize--) | Document size in bytes. |
### getType() {#getType--}
```
public abstract FileType getType()
```


Gets the file type.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public abstract IPageInfo[] getPages()
```


Defines document pages collection.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


The document pages count.

**Returns:**
int
### getSize() {#getSize--}
```
public abstract long getSize()
```


Document size in bytes.

**Returns:**
long
