---
title: "OleSpreadsheetOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la importación del documento incrustado a Spreadsheet mediante OLE."
type: docs
weight: 20
url: /es/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Proporciona opciones para la importación del documento incrustado a Spreadsheet mediante OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Inicializa una nueva instancia de la clase [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Inicializa una nueva instancia de la clase [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Inicializa una nueva instancia de la clase [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | El índice de fila superior izquierda. |
| [setRowIndex(int value)](#setRowIndex-int-) | El índice de fila superior izquierda. |
| [getColumnIndex()](#getColumnIndex--) | El índice de columna superior izquierda. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | El índice de columna superior izquierda. |
| [getWidth()](#getWidth--) | El ancho de la imagen del objeto Ole. |
| [setWidth(int value)](#setWidth-int-) | El ancho de la imagen del objeto Ole. |
| [getHeight()](#getHeight--) | La altura de la imagen del objeto Ole. |
| [setHeight(int value)](#setHeight-int-) | La altura de la imagen del objeto Ole. |
| [getImageData()](#getImageData--) | Los datos de la imagen del objeto Ole. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectData | byte[] | Los datos del objeto incrustado. |
| imageData | byte[] | Los datos de imagen del objeto incrustado. |
| extensión | java.lang.String | La extensión del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| imageData | byte[] | Los datos de imagen del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


El índice de fila superior izquierda.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


El índice de fila superior izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


El índice de columna superior izquierda.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


El índice de columna superior izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


El ancho de la imagen del objeto Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


El ancho de la imagen del objeto Ole.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


La altura de la imagen del objeto Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


La altura de la imagen del objeto Ole.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Los datos de la imagen del objeto Ole.

**Returns:**
byte[]
