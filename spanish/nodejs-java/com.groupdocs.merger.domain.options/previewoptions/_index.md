---
title: "PreviewOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Representa opciones de vista previa del documento."
type: docs
weight: 29
url: /es/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Representa opciones de vista previa del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Ancho de vista previa. |
| [setWidth(int value)](#setWidth-int-) | Ancho de vista previa. |
| [getHeight()](#getHeight--) | Altura de vista previa. |
| [setHeight(int value)](#setHeight-int-) | Altura de vista previa. |
| [getResolution()](#getResolution--) | Resolución de imagen. |
| [setResolution(int value)](#setResolution-int-) | Resolución de imagen. |
| [getMode()](#getMode--) | Modo de vista previa. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valida las opciones de vista previa. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Obtiene la ruta completa del archivo del documento previsualizado por número de página con la extensión definida. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory para crear o liberar el flujo de vista previa de la página de salida. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| previewMode | int | El modo de vista previa del Modo (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| previewMode | int | El modo de vista previa del Modo (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Números de página. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| previewMode | int | El modo de vista previa del Modo (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| previewMode | int | El modo de vista previa del Modo (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ancho de vista previa.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ancho de vista previa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altura de vista previa.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altura de vista previa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Resolución de imagen.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Resolución de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Modo de vista previa.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valida las opciones de vista previa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory para crear o liberar el flujo de vista previa de la página de salida.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
