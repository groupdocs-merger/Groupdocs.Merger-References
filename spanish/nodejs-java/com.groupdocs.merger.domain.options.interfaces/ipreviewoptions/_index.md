---
title: "IPreviewOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Interfaz para las opciones de vista previa."
type: docs
weight: 28
url: /es/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Interfaz para las opciones de vista previa.
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Ancho de vista previa. |
| [setWidth(int value)](#setWidth-int-) | Ancho de vista previa. |
| [getHeight()](#getHeight--) | Altura de vista previa. |
| [setHeight(int value)](#setHeight-int-) | Altura de vista previa. |
| [getResolution()](#getResolution--) | Resolución de imagen. |
| [setResolution(int value)](#setResolution-int-) | Resolución de imagen. |
| [getMode()](#getMode--) | Obtiene el modo de vista previa. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valida las opciones de división. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Obtiene la ruta completa del archivo del documento previsualizado por número de página con la extensión definida. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegado que define el método para crear el flujo de salida de la vista previa de la página. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Ancho de vista previa.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Ancho de vista previa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Altura de vista previa.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Altura de vista previa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Resolución de imagen.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Resolución de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Obtiene el modo de vista previa.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valida las opciones de división.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo de la clase [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Obtiene la ruta completa del archivo del documento previsualizado por número de página con la extensión definida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int | Número de página de la vista previa. |
| extensión | java.lang.String | Extensión del archivo. |

**Returns:**
java.lang.String - La ruta completa del archivo.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Delegado que define el método para crear el flujo de salida de la vista previa de la página.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
