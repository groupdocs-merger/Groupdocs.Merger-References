---
title: TextSplitOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Provides options for the document text splitting.
type: docs
weight: 37
url: /java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Provides options for the document text splitting.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class. |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class. |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class. |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getFilePathInfo()](#getFilePathInfo--) |  |
| [getMode()](#getMode--) | Mode for text splitting. |
| [getLineNumbers()](#getLineNumbers--) | Line numbers for text splitting. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validates the split options. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Gets the full file path of splitted document by index with defined extension. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory for create or release output page preview stream. |
| [setSplitStreamFactory(SplitStreamFactory mSplitStreamFactory)](#setSplitStreamFactory-com.groupdocs.merger.domain.common.SplitStreamFactory-) |  |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lineNumbers | int[] | Line numbers for text splitting. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mode | int | Mode for text splitting. |
| lineNumbers | int[] | Line numbers for text splitting. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already defined extension. |
| lineNumbers | int[] | Line numbers for text splitting. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | java.lang.String | The file path format e.g. 'c:/split\{0\}.doc' or 'c:/split\{0\}.\{1\}' with already defined extension. |
| mode | int | Mode for text splitting. |
| lineNumbers | int[] | Line numbers for text splitting. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| lineNumbers | int[] | Line numbers for text splitting. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Initializes a new instance of the [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | The method that instantiates stream used to write output split data. |
| mode | int | Mode for text splitting. |
| lineNumbers | int[] | Line numbers for text splitting. |

### getFilePathInfo() {#getFilePathInfo--}
```
public final SplitFilePathInfo getFilePathInfo()
```




**Returns:**
[SplitFilePathInfo](../../com.groupdocs.merger.domain.result.filepath/splitfilepathinfo)
### getMode() {#getMode--}
```
public final int getMode()
```


Mode for text splitting.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Line numbers for text splitting.

**Returns:**
int[]
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


Gets the full file path of splitted document by index with defined extension.

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
### setSplitStreamFactory(SplitStreamFactory mSplitStreamFactory) {#setSplitStreamFactory-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public void setSplitStreamFactory(SplitStreamFactory mSplitStreamFactory)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mSplitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) |  |

