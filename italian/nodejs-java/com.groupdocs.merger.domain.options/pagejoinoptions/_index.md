---
title: "PageJoinOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'unione dei documenti."
type: docs
weight: 25
url: /it/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Fornisce opzioni per l'unione dei documenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Il tipo del file da unire. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumbers | int[] | Numeri di pagina. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |
| pageNumbers | int[] | Numeri di pagina. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### getType() {#getType--}
```
public final FileType getType()
```


Il tipo del file da unire.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
