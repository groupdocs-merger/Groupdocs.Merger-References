---
title: "WordJoinOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Le opzioni di unione di Word."
type: docs
weight: 43
url: /it/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Le opzioni di unione di Word.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMode()](#getMode--) | La modalità di unione Word. |
| [setMode(int value)](#setMode-int-) | La modalità di unione Word. |
| [getCompliance()](#getCompliance--) | Modalità di conformità per il formato Word Ooxml |
| [setCompliance(int value)](#setCompliance-int-) | Modalità di conformità per il formato Word Ooxml |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumbers | int[] | Numeri di pagina. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |
| pageNumbers | int[] | Numeri di pagina. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file da unire. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### getMode() {#getMode--}
```
public final int getMode()
```


La modalità di unione Word.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


La modalità di unione Word.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Modalità di conformità per il formato Word Ooxml

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Modalità di conformità per il formato Word Ooxml

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

