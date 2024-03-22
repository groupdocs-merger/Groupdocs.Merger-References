---
title: OrientationOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Provides options for the page orientation.
type: docs
weight: 23
url: /nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Provides options for the page orientation.
## Constructors

| Constructor | Description |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class. |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getMode()](#getMode--) | Gets the mode for the page orientation. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientationMode | int | The orientation mode of [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientationMode | int | The orientation mode of [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| pageNumbers | int[] | Page numbers. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientationMode | int | The orientation mode of [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Initializes a new instance of the [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientationMode | int | The orientation mode of [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | The start page number. |
| endNumber | int | The end page number. |
| mode | int | The range mode. |

### getMode() {#getMode--}
```
public final int getMode()
```


Gets the mode for the page orientation.

**Returns:**
int
