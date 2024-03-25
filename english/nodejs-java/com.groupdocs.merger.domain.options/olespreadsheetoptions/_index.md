---
title: OleSpreadsheetOptions
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: Provides options for import of the embedded document to Spreadsheet via OLE.
type: docs
weight: 20
url: /nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Provides options for import of the embedded document to Spreadsheet via OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Constructors

| Constructor | Description |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Initializes a new instance of the [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) class. |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Initializes a new instance of the [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) class. |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Initializes a new instance of the [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | The upper left row index. |
| [setRowIndex(int value)](#setRowIndex-int-) | The upper left row index. |
| [getColumnIndex()](#getColumnIndex--) | The upper left column index. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | The upper left column index. |
| [getWidth()](#getWidth--) | The width of the Ole object image. |
| [setWidth(int value)](#setWidth-int-) | The width of the Ole object image. |
| [getHeight()](#getHeight--) | The height of the Ole object image. |
| [setHeight(int value)](#setHeight-int-) | The height of the Ole object image. |
| [getImageData()](#getImageData--) | The data of the Ole object image. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initializes a new instance of the [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectData | byte[] | The data of the embedded object. |
| imageData | byte[] | The image data of the embedded object. |
| extension | java.lang.String | The extension of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Initializes a new instance of the [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| imageData | byte[] | The image data of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Initializes a new instance of the [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


The upper left row index.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


The upper left row index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


The upper left column index.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


The upper left column index.

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
