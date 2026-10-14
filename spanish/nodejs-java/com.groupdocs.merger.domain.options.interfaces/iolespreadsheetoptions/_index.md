---
title: "IOleSpreadsheetOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para opciones de importación del documento incrustado a Spreadsheet mediante OLE."
type: docs
weight: 19
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Interfaz para opciones de importación del documento incrustado a Spreadsheet mediante OLE.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | El índice de fila superior izquierda. |
| [setRowIndex(int value)](#setRowIndex-int-) | El índice de fila superior izquierda. |
| [getColumnIndex()](#getColumnIndex--) | El índice de columna superior izquierda. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | El índice de columna superior izquierda. |
| [getImageData()](#getImageData--) | Los datos de la imagen del objeto Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


El índice de fila superior izquierda.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


El índice de fila superior izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


El índice de columna superior izquierda.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


El índice de columna superior izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Los datos de la imagen del objeto Ole.

**Returns:**
byte[]
