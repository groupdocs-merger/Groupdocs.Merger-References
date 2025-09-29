---
title: PreviewOptions
second_title: GroupDocs.Merger for Java API Reference
description: Represents document preview options.
type: docs
weight: 31
url: /java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Represents document preview options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Preview width. |
| [setWidth(int value)](#setWidth-int-) | Preview width. |
| [getHeight()](#getHeight--) | Preview height. |
| [setHeight(int value)](#setHeight-int-) | Preview height. |
| [getResolution()](#getResolution--) | Image resolution. |
| [setResolution(int value)](#setResolution-int-) | Image resolution. |
| [getMode()](#getMode--) | Mode for preview. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validates the preview options. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Gets the full file path of previewed document by page number with defined extension. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory for create or release output page preview stream. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | The method that instantiates stream used to write output page data. |
| previewMode | int | The preview mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | The method that instantiates stream used to write output page data. |
| previewMode | int | The preview mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Page numbers. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | The method that instantiates stream used to write output page data. |
| previewMode | int | The preview mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | The method that instantiates stream used to write output page data. |
| previewMode | int | The preview mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Preview width.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Preview width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Preview height.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Preview height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Image resolution.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Image resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Mode for preview.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validates the preview options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The file type. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory for create or release output page preview stream.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
