---
title: RotateOptions
second_title: GroupDocs.Merger for Java API Reference
description: Provides options for the page rotation.
type: docs
weight: 31
url: /java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Provides options for the page rotation.
## Constructors

| Constructor | Description |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class. |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMode()](#getMode--) | Gets the mode for rotating (90, 180 or 270 degrees). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateMode | int | The rotating mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateMode | int | The rotating mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Page numbers. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateMode | int | The rotating mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotateMode | int | The rotating mode of  Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getMode() {#getMode--}
```
public final int getMode()
```


Gets the mode for rotating (90, 180 or 270 degrees).

**Returns:**
int
