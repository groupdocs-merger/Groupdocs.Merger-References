---
title: "OleWordProcessingOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la importación del documento incrustado a Word processing mediante OLE."
type: docs
weight: 21
url: /es/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Proporciona opciones para la importación del documento incrustado a Word processing mediante OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Inicializa una nueva instancia de la clase [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Inicializa una nueva instancia de la clase [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Inicializa una nueva instancia de la clase [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLeft()](#getLeft--) | La coordenada izquierda de la imagen del objeto Ole. |
| [setLeft(int value)](#setLeft-int-) | La coordenada izquierda de la imagen del objeto Ole. |
| [getTop()](#getTop--) | La coordenada superior de la imagen del objeto Ole. |
| [setTop(int value)](#setTop-int-) | La coordenada superior de la imagen del objeto Ole. |
| [getWidth()](#getWidth--) | El ancho de la imagen del objeto Ole. |
| [setWidth(int value)](#setWidth-int-) | El ancho de la imagen del objeto Ole. |
| [getHeight()](#getHeight--) | La altura de la imagen del objeto Ole. |
| [setHeight(int value)](#setHeight-int-) | La altura de la imagen del objeto Ole. |
| [getImageData()](#getImageData--) | Los datos de la imagen del objeto Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectData | byte[] | Los datos del objeto incrustado. |
| imageData | byte[] | Los datos de imagen del objeto incrustado. |
| extensión | java.lang.String | La extensión del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| imageData | byte[] | Los datos de imagen del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


La coordenada izquierda de la imagen del objeto Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


La coordenada izquierda de la imagen del objeto Ole.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


La coordenada superior de la imagen del objeto Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


La coordenada superior de la imagen del objeto Ole.

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
