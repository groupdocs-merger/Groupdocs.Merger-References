---
title: "TextSplitOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la división de texto del documento."
type: docs
weight: 39
url: /es/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Proporciona opciones para la división de texto del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMode()](#getMode--) | Modo para la división de texto. |
| [getLineNumbers()](#getLineNumbers--) | Números de línea para la división de texto. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valida las opciones de división. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtiene la ruta completa del archivo del documento dividido por índice con la extensión definida. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory para crear o liberar el flujo de vista previa de página de salida. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| lineNumbers | int[] | Números de línea para la división de texto. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | int | Modo para la división de texto. |
| lineNumbers | int[] | Números de línea para la división de texto. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de ruta de archivo, p. ej. 'c:/split\\{0\\}.doc' o 'c:/split\\{0\\}.\\{1\\}' con la extensión ya definida. |
| lineNumbers | int[] | Números de línea para la división de texto. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de ruta de archivo, p. ej. 'c:/split\\{0\\}.doc' o 'c:/split\\{0\\}.\\{1\\}' con la extensión ya definida. |
| mode | int | Modo para la división de texto. |
| lineNumbers | int[] | Números de línea para la división de texto. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| lineNumbers | int[] | Números de línea para la división de texto. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Inicializa una nueva instancia de la clase [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| mode | int | Modo para la división de texto. |
| lineNumbers | int[] | Números de línea para la división de texto. |

### getMode() {#getMode--}
```
public final int getMode()
```


Modo para la división de texto.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Números de línea para la división de texto.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valida las opciones de división.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo de la clase [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Obtiene la ruta completa del archivo del documento dividido por índice con la extensión definida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice del documento dividido. |
| extensión | java.lang.String | Extensión del archivo. |

**Returns:**
java.lang.String - La ruta completa del archivo.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory para crear o liberar el flujo de vista previa de página de salida.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
