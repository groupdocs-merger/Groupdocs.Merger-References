---
title: OlePresentationOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Provides options for import of the embedded document to Presentation via OLE.
type: docs
weight: 19
url: /java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Provides options for import of the embedded document to Presentation via OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Constructors

| Constructor | Description |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Initializes a new instance of the [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) class. |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Initializes a new instance of the [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | The X coordinate of the embedded object frame. |
| [setX(int value)](#setX-int-) | The X coordinate of the embedded object frame. |
| [getY()](#getY--) | The Y coordinate of the embedded object frame. |
| [setY(int value)](#setY-int-) | The Y coordinate of the embedded object frame. |
| [getWidth()](#getWidth--) | The width of the embedded object frame. |
| [setWidth(int value)](#setWidth-int-) | The width of the embedded object frame. |
| [getHeight()](#getHeight--) | The height of the embedded object frame. |
| [setHeight(int value)](#setHeight-int-) | The height of the embedded object frame. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Initializes a new instance of the [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectData | byte[] | The data of the embedded object. |
| extension | java.lang.String | The extension of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Initializes a new instance of the [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### getX() {#getX--}
```
public final int getX()
```


The X coordinate of the embedded object frame.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


The X coordinate of the embedded object frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


The Y coordinate of the embedded object frame.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


The Y coordinate of the embedded object frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


The width of the embedded object frame.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


The width of the embedded object frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


The height of the embedded object frame.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


The height of the embedded object frame.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

