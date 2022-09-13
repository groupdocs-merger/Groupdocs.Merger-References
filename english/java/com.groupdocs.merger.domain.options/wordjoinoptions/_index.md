---
title: WordJoinOptions
second_title: GroupDocs.Merger for Java API Reference
description:  The Word join options.
type: docs
weight: 40
url: /java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions)
```
public class WordJoinOptions extends JoinOptions
```

The Word join options.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMode()](#getMode--) | The Word join mode. |
| [setMode(int value)](#setMode-int-) | The Word join mode. |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Page numbers. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| pageNumbers | int[] | Page numbers. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getMode() {#getMode--}
```
public final int getMode()
```


The Word join mode.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


The Word join mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

