---
title: OleDiagramOptions
second_title: GroupDocs.Merger for Java API Reference
description:  Provides options for import of the embedded document to Diagram via OLE.
type: docs
weight: 18
url: /java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Provides options for import of the embedded document to Diagram via OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructors

| Constructor | Description |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Initializes a new instance of the [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) class. |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Initializes a new instance of the [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) class. |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Initializes a new instance of the [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [setX(int value)](#setX-int-) | The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [getY()](#getY--) | The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [setY(int value)](#setY-int-) | The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [getWidth()](#getWidth--) | The width of the embedded object shape in inches. |
| [setWidth(int value)](#setWidth-int-) | The width of the embedded object shape in inches. |
| [getHeight()](#getHeight--) | The height of the embedded object shape in inches. |
| [setHeight(int value)](#setHeight-int-) | The height of the embedded object shape in inches. |
| [getImageData()](#getImageData--) | The image data of the embedded object. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initializes a new instance of the [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectData | byte[] | The data of the embedded object. |
| imageData | byte[] | The image data of the embedded object. |
| extension | java.lang.String | The extension of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Initializes a new instance of the [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| imageData | byte[] | The image data of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Initializes a new instance of the [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### getX() {#getX--}
```
public final int getX()
```


The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


The width of the embedded object shape in inches.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


The width of the embedded object shape in inches.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


The height of the embedded object shape in inches.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


The height of the embedded object shape in inches.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


The image data of the embedded object.

**Returns:**
byte[]
