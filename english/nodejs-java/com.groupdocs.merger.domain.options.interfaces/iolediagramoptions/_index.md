---
title: IOleDiagramOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Interface for import options of the embedded document to Diagram via OLE.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Interface for import options of the embedded document to Diagram via OLE.
## Methods

| Method | Description |
| --- | --- |
| [getX()](#getX--) | The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [setX(int value)](#setX-int-) | The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [getY()](#getY--) | The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [setY(int value)](#setY-int-) | The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page. |
| [getImageData()](#getImageData--) | The image data of the embedded object. |
### getX() {#getX--}
```
public abstract int getX()
```


The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


The X coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


The Y coordinate of the embedded object shape's pin (center of rotation) in relation to the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


The image data of the embedded object.

**Returns:**
byte[]
