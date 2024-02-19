---
title: PageJoinOptions
second_title: GroupDocs.Merger for Java API Reference
description: Provides options for the document joining.
type: docs
weight: 25
url: /java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Provides options for the document joining.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The type of the file to join. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Page numbers. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| pageNumbers | int[] | Page numbers. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getType() {#getType--}
```
public final FileType getType()
```


The type of the file to join.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
