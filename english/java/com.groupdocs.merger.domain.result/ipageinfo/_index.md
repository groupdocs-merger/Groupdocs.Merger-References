---
title: IPageInfo
second_title: GroupDocs.Merger for Java API Reference
description: Interface for the page description properties.
type: docs
weight: 13
url: /java/com.groupdocs.merger.domain.result/ipageinfo/
---```
public interface IPageInfo
```

Interface for the page description properties.
## Methods

| Method | Description |
| --- | --- |
| [getDocument()](#getDocument--) | Gets the document info. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Gets the document info. |
| [getNumber()](#getNumber--) | Gets the page number. |
| [getVisible()](#getVisible--) | Indicates whether page is visibile or not. |
| [getWidth()](#getWidth--) | Gets page width in pixels when converted to image. |
| [getHeight()](#getHeight--) | Gets page height in pixels when converted to image. |
### getDocument() {#getDocument--}
```
public abstract DocumentInfo getDocument()
```


Gets the document info.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public abstract void setDocument(DocumentInfo value)
```


Gets the document info.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Gets the page number.

**Returns:**
int
### getVisible() {#getVisible--}
```
public abstract boolean getVisible()
```


Indicates whether page is visibile or not.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Gets page width in pixels when converted to image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Gets page height in pixels when converted to image.

**Returns:**
int
