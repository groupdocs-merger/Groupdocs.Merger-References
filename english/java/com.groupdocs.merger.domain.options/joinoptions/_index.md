---
title: JoinOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Provides options for the document joining.
type: docs
weight: 15
url: /java/com.groupdocs.merger.domain.options/joinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions)
```
public class JoinOptions extends PageOptions implements IJoinOptions
```

Provides options for the document joining.
## Constructors

| Constructor | Description |
| --- | --- |
| [JoinOptions()](#JoinOptions--) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(int[] pageNumbers)](#JoinOptions-int---) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(int startNumber, int endNumber)](#JoinOptions-int-int-) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(int startNumber, int endNumber, int mode)](#JoinOptions-int-int-int-) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(FileType fileType)](#JoinOptions-com.groupdocs.merger.domain.FileType-) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(FileType fileType, int[] pageNumbers)](#JoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(FileType fileType, int startNumber, int endNumber)](#JoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
| [JoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#JoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | The type of the file to join. |
### JoinOptions() {#JoinOptions--}
```
public JoinOptions()
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

### JoinOptions(int[] pageNumbers) {#JoinOptions-int---}
```
public JoinOptions(int[] pageNumbers)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumbers | int[] | Page numbers. |

### JoinOptions(int startNumber, int endNumber) {#JoinOptions-int-int-}
```
public JoinOptions(int startNumber, int endNumber)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### JoinOptions(int startNumber, int endNumber, int mode) {#JoinOptions-int-int-int-}
```
public JoinOptions(int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### JoinOptions(FileType fileType) {#JoinOptions-com.groupdocs.merger.domain.FileType-}
```
public JoinOptions(FileType fileType)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |

### JoinOptions(FileType fileType, int[] pageNumbers) {#JoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public JoinOptions(FileType fileType, int[] pageNumbers)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| pageNumbers | int[] | Page numbers. |

### JoinOptions(FileType fileType, int startNumber, int endNumber) {#JoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public JoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The type of the file to join. |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### JoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#JoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public JoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) class.

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
