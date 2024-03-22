---
title: OleWordProcessingOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Provides options for import of the embedded document to Word processing via OLE.
type: docs
weight: 21
url: /nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Provides options for import of the embedded document to Word processing via OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Constructors

| Constructor | Description |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Initializes a new instance of the [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) class. |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Initializes a new instance of the [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) class. |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Initializes a new instance of the [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getLeft()](#getLeft--) | The left coordinate of the Ole object image. |
| [setLeft(int value)](#setLeft-int-) | The left coordinate of the Ole object image. |
| [getTop()](#getTop--) | The top coordinate of the Ole object image. |
| [setTop(int value)](#setTop-int-) | The top coordinate of the Ole object image. |
| [getWidth()](#getWidth--) | The width of the Ole object image. |
| [setWidth(int value)](#setWidth-int-) | The width of the Ole object image. |
| [getHeight()](#getHeight--) | The height of the Ole object image. |
| [setHeight(int value)](#setHeight-int-) | The height of the Ole object image. |
| [getImageData()](#getImageData--) | The data of the Ole object image. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initializes a new instance of the [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectData | byte[] | The data of the embedded object. |
| imageData | byte[] | The image data of the embedded object. |
| extension | java.lang.String | The extension of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Initializes a new instance of the [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| imageData | byte[] | The image data of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Initializes a new instance of the [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


The left coordinate of the Ole object image.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


The left coordinate of the Ole object image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


The top coordinate of the Ole object image.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


The top coordinate of the Ole object image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


The width of the Ole object image.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


The width of the Ole object image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


The height of the Ole object image.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


The height of the Ole object image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


The data of the Ole object image.

**Returns:**
byte[]
