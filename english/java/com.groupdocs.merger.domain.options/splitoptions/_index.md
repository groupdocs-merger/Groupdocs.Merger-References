---
title: SplitOptions
second_title: GroupDocs.Merger for Java API Reference
description: Provides options for the document page splitting.
type: docs
weight: 38
url: /java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Provides options for the document page splitting.
## Constructors

| Constructor | Description |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMode()](#getMode--) | Gets the mode for page splitting. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validates the split options. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Gets the full file path of splitted document by index with pre-defined extension. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory for create or release output page preview stream. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Page numbers. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already pre-defined extension. |
| pageNumbers | int[] | Page numbers. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already pre-defined extension. |
| pageNumbers | int[] | Page numbers. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already pre-defined extension. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already pre-defined extension. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already pre-defined extension. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | java.lang.Integer | The range mode. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already pre-defined extension. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| pageNumbers | int[] | Page numbers. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| pageNumbers | int[] | Page numbers. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | java.lang.Integer | The range mode. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| splitMode | int | The splitting mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getMode() {#getMode--}
```
public final int getMode()
```


Gets the mode for page splitting.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validates the split options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The file type of [FileType](../../com.groupdocs.merger.domain/filetype) class. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Gets the full file path of splitted document by index with pre-defined extension.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of splitted document. |
| extension | java.lang.String | Extension of file. |

**Returns:**
java.lang.String - The full file path.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory for create or release output page preview stream.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
