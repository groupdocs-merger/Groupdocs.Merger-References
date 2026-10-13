---
title: "IDocumentInfo"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "문서 설명 속성을 위한 인터페이스입니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.merger.domain.result/idocumentinfo/
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
