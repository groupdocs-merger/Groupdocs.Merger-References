---
title: "SplitOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la división de páginas del documento."
type: docs
weight: 36
url: /es/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Proporciona opciones para la división de páginas del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMode()](#getMode--) | Obtiene el modo para dividir páginas. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valida las opciones de división. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtiene la ruta completa del archivo dividido por índice con la extensión predefinida. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory para crear o liberar el flujo de vista previa de página de salida. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumbers | int[] | Números de página. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de la ruta del archivo, por ejemplo 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con la extensión ya predefinida. |
| pageNumbers | int[] | Números de página. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de la ruta del archivo, por ejemplo 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con la extensión ya predefinida. |
| pageNumbers | int[] | Números de página. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de la ruta del archivo, por ejemplo 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con la extensión ya predefinida. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de la ruta del archivo, por ejemplo 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con la extensión ya predefinida. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de la ruta del archivo, por ejemplo 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con la extensión ya predefinida. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | java.lang.Integer | El modo de rango. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePathFormat | java.lang.String | El formato de la ruta del archivo, por ejemplo 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con la extensión ya predefinida. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| pageNumbers | int[] | Números de página. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| pageNumbers | int[] | Números de página. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | java.lang.Integer | El modo de rango. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | El método que instancia el flujo utilizado para escribir los datos divididos de salida. |
| splitMode | int | El modo de división del Modo (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtiene el modo para dividir páginas.

**Returns:**
int
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


Obtiene la ruta completa del archivo dividido por índice con la extensión predefinida.

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
