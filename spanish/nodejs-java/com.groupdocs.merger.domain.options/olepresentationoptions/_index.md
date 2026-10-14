---
title: "OlePresentationOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la importación del documento incrustado a Presentation mediante OLE."
type: docs
weight: 19
url: /es/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Proporciona opciones para la importación del documento incrustado a Presentation mediante OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Inicializa una nueva instancia de la clase [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Inicializa una nueva instancia de la clase [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getX()](#getX--) | La coordenada X del marco del objeto incrustado. |
| [setX(int value)](#setX-int-) | La coordenada X del marco del objeto incrustado. |
| [getY()](#getY--) | La coordenada Y del marco del objeto incrustado. |
| [setY(int value)](#setY-int-) | La coordenada Y del marco del objeto incrustado. |
| [getWidth()](#getWidth--) | El ancho del marco del objeto incrustado. |
| [setWidth(int value)](#setWidth-int-) | El ancho del marco del objeto incrustado. |
| [getHeight()](#getHeight--) | La altura del marco del objeto incrustado. |
| [setHeight(int value)](#setHeight-int-) | La altura del marco del objeto incrustado. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Inicializa una nueva instancia de la clase [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectData | byte[] | Los datos del objeto incrustado. |
| extensión | java.lang.String | La extensión del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Inicializa una nueva instancia de la clase [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### getX() {#getX--}
```
public final int getX()
```


La coordenada X del marco del objeto incrustado.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


La coordenada X del marco del objeto incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


La coordenada Y del marco del objeto incrustado.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


La coordenada Y del marco del objeto incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


El ancho del marco del objeto incrustado.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


El ancho del marco del objeto incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


La altura del marco del objeto incrustado.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


La altura del marco del objeto incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

