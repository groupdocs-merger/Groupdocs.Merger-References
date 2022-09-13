---
title: PageInfo
second_title: GroupDocs.Merger for Java API Reference
description:  Defines page description properties.
type: docs
weight: 11
url: /java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Defines page description properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Initializes new instance of [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) class. |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Initializes new instance of [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getNumber()](#getNumber--) | Gets the page number. |
| [setNumber(int value)](#setNumber-int-) |  |
| [getVisible()](#getVisible--) | Indicates whether page is visibile or not. |
| [setVisible(boolean value)](#setVisible-boolean-) |  |
| [getWidth()](#getWidth--) | Gets page width in pixels when converted to image. |
| [setWidth(int value)](#setWidth-int-) |  |
| [getHeight()](#getHeight--) | Gets page height in pixels when converted to image. |
| [setHeight(int value)](#setHeight-int-) |  |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Initializes new instance of [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| visible | boolean | The page visibility indicator. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Initializes new instance of [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | The page number. |
| visible | boolean | The page visibility indicator. |
| width | int | The width of the page in pixels when viewing as JPG or PNG. |
| height | int | The height of the page in pixels when viewing as JPG or PNG. |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Gets the page number.

**Returns:**
int
### setNumber(int value) {#setNumber-int-}
```
public final void setNumber(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Indicates whether page is visibile or not.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Gets page width in pixels when converted to image.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Gets page height in pixels when converted to image.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

