---
title: "OleDiagramOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la importación del documento incrustado a Diagram mediante OLE."
type: docs
weight: 18
url: /es/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Proporciona opciones para la importación del documento incrustado a Diagram mediante OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Inicializa una nueva instancia de la clase [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Inicializa una nueva instancia de la clase [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Inicializa una nueva instancia de la clase [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getX()](#getX--) | La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [setX(int value)](#setX-int-) | La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [getY()](#getY--) | La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [setY(int value)](#setY-int-) | La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página. |
| [getWidth()](#getWidth--) | El ancho de la forma del objeto incrustado en pulgadas. |
| [setWidth(int value)](#setWidth-int-) | El ancho de la forma del objeto incrustado en pulgadas. |
| [getHeight()](#getHeight--) | La altura de la forma del objeto incrustado en pulgadas. |
| [setHeight(int value)](#setHeight-int-) | La altura de la forma del objeto incrustado en pulgadas. |
| [getImageData()](#getImageData--) | Los datos de imagen del objeto incrustado. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectData | byte[] | Los datos del objeto incrustado. |
| imageData | byte[] | Los datos de imagen del objeto incrustado. |
| extensión | java.lang.String | La extensión del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| imageData | byte[] | Los datos de imagen del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Inicializa una nueva instancia de la clase [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### getX() {#getX--}
```
public final int getX()
```


La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


La coordenada X del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


La coordenada Y del pin de la forma del objeto incrustado (centro de rotación) en relación con la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


El ancho de la forma del objeto incrustado en pulgadas.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


El ancho de la forma del objeto incrustado en pulgadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


La altura de la forma del objeto incrustado en pulgadas.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


La altura de la forma del objeto incrustado en pulgadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Los datos de imagen del objeto incrustado.

**Returns:**
byte[]
