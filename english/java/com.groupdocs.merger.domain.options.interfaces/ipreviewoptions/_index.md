---
title: IPreviewOptions
second_title: GroupDocs.Merger for Java API Reference
description: Interface for the preview options.
type: docs
weight: 28
url: /java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Interface for the preview options.
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Preview width. |
| [setWidth(int value)](#setWidth-int-) | Preview width. |
| [getHeight()](#getHeight--) | Preview height. |
| [setHeight(int value)](#setHeight-int-) | Preview height. |
| [getMode()](#getMode--) | Gets the mode for preview. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validates the split options. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Gets the full file path of previewed document by page number with defined extension. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegate that defines method to create output page preview stream. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Preview width.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Preview width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Preview height.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Preview height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Gets the mode for preview.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Validates the split options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The file type of [FileType](../../com.groupdocs.merger.domain/filetype) class. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Gets the full file path of previewed document by page number with defined extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Page number of preview. |
| extension | java.lang.String | Extension of file. |

**Returns:**
java.lang.String - The full file path.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Delegate that defines method to create output page preview stream.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
