---
title: "PageJoinOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la unión de documentos."
type: docs
weight: 25
url: /es/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Proporciona opciones para la unión de documentos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getType()](#getType--) | El tipo de archivo a combinar. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumbers | int[] | Números de página. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |
| pageNumbers | int[] | Números de página. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo de archivo a combinar. |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### getType() {#getType--}
```
public final FileType getType()
```


El tipo de archivo a combinar.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
