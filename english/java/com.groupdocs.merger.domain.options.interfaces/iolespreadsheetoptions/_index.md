---
title: IOleSpreadsheetOptions
second_title: GroupDocs.Signature for Java API Reference
description: Interface for import options of the embedded document to Spreadsheet via OLE.
type: docs
weight: 18
url: /java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Interface for import options of the embedded document to Spreadsheet via OLE.
## Methods

| Method | Description |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | The upper left row index. |
| [setRowIndex(int value)](#setRowIndex-int-) | The upper left row index. |
| [getColumnIndex()](#getColumnIndex--) | The upper left column index. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | The upper left column index. |
| [getImageData()](#getImageData--) | The data of the Ole object image. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


The upper left row index.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


The upper left row index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


The upper left column index.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


The upper left column index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


The data of the Ole object image.

**Returns:**
byte[]
