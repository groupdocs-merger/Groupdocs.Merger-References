---
title: "WordJoinOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Las opciones de unión de Word."
type: docs
weight: 43
url: /es/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Las opciones de unión de Word.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMode()](#getMode--) | El modo de unión de Word. |
| [setMode(int value)](#setMode-int-) | El modo de unión de Word. |
| [getCompliance()](#getCompliance--) | Modo de cumplimiento para el formato Word Ooxml |
| [setCompliance(int value)](#setCompliance-int-) | Modo de cumplimiento para el formato Word Ooxml |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumbers | int[] | Números de página. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |
| pageNumbers | int[] | Números de página. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### getMode() {#getMode--}
```
public final int getMode()
```


El modo de unión de Word.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


El modo de unión de Word.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Modo de cumplimiento para el formato Word Ooxml

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Modo de cumplimiento para el formato Word Ooxml

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

