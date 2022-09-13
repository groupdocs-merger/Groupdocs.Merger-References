---
title: PreviewOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Represents document preview options.
type: docs
weight: 27
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
| [PreviewOptions(int previewMode, int[] pageNumbers)](#PreviewOptions-int-int---) |  |
| [PreviewOptions(int previewMode, int startNumber, int endNumber)](#PreviewOptions-int-int-int-) |  |
| [PreviewOptions(int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-int-int-int-int-) |  |
| [PreviewOptions(String filePathFormat, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-java.lang.String-int-int-int-int-) |  |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFilePathInfo()](#getFilePathInfo--) |  |
| [getWidth()](#getWidth--) | Preview width. |
| [setWidth(int value)](#setWidth-int-) | Preview width. |
| [getHeight()](#getHeight--) | Preview height. |
| [setHeight(int value)](#setHeight-int-) | Preview height. |
| [getMode()](#getMode--) | Mode for preview. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validates the preview options. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Gets the full file path of previewed document by page number with defined extension. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory for create or release output page preview stream. |
| [setPageStreamFactory(PageStreamFactory mPageStreamFactory)](#setPageStreamFactory-com.groupdocs.merger.domain.common.PageStreamFactory-) |  |
### PreviewOptions(int previewMode, int[] pageNumbers) {#PreviewOptions-int-int---}
```
public PreviewOptions(int previewMode, int[] pageNumbers)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewMode | int |  |
| pageNumbers | int[] |  |

### PreviewOptions(int previewMode, int startNumber, int endNumber) {#PreviewOptions-int-int-int-}
```
public PreviewOptions(int previewMode, int startNumber, int endNumber)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewMode | int |  |
| startNumber | int |  |
| endNumber | int |  |

### PreviewOptions(int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-int-int-int-int-}
```
public PreviewOptions(int previewMode, int startNumber, int endNumber, int mode)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewMode | int |  |
| startNumber | int |  |
| endNumber | int |  |
| mode | int |  |

### PreviewOptions(String filePathFormat, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-java.lang.String-int-int-int-int-}
```
public PreviewOptions(String filePathFormat, int previewMode, int startNumber, int endNumber, int mode)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String |  |
| previewMode | int |  |
| startNumber | int |  |
| endNumber | int |  |
| mode | int |  |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | The method that instantiates stream used to write output page data. |
| previewMode | int | The preview mode of \`\`\` Mode \`\`\`([\#getMode](../../null/\#getMode)/[\#setMode(int)](../../null/\#setMode-int-)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Initializes a new instance of the [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | The method that instantiates stream used to write output page data. |
| previewMode | int | The preview mode of \`\`\` Mode \`\`\`([\#getMode](../../null/\#getMode)/[\#setMode(int)](../../null/\#setMode-int-)) |
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
| previewMode | int | The preview mode of \`\`\` Mode \`\`\`([\#getMode](../../null/\#getMode)/[\#setMode(int)](../../null/\#setMode-int-)) |
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
| previewMode | int | The preview mode of \`\`\` Mode \`\`\`([\#getMode](../../null/\#getMode)/[\#setMode(int)](../../null/\#setMode-int-)) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getFilePathInfo() {#getFilePathInfo--}
```
public PreviewFilePathInfo getFilePathInfo()
```




**Returns:**
[PreviewFilePathInfo](../../com.groupdocs.merger.domain.result.filepath/previewfilepathinfo)
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
### setPageStreamFactory(PageStreamFactory mPageStreamFactory) {#setPageStreamFactory-com.groupdocs.merger.domain.common.PageStreamFactory-}
```
public void setPageStreamFactory(PageStreamFactory mPageStreamFactory)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mPageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) |  |

