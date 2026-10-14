---
title: "SplitOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per la divisione delle pagine del documento."
type: docs
weight: 36
url: /it/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Fornisce opzioni per la divisione delle pagine del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMode()](#getMode--) | Ottiene la modalità per la divisione delle pagine. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Convalida le opzioni di divisione. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Restituisce il percorso completo del file del documento diviso per indice con estensione predefinita. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory per creare o rilasciare lo stream di anteprima della pagina di output. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumbers | int[] | Numeri di pagina. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già predefinita. |
| pageNumbers | int[] | Numeri di pagina. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già predefinita. |
| pageNumbers | int[] | Numeri di pagina. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già predefinita. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già predefinita. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già predefinita. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | java.lang.Integer | La modalità di intervallo. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già predefinita. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| pageNumbers | int[] | Numeri di pagina. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| pageNumbers | int[] | Numeri di pagina. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | java.lang.Integer | La modalità di intervallo. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| splitMode | int | La modalità di divisione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ottiene la modalità per la divisione delle pagine.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Convalida le opzioni di divisione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file della classe [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Restituisce il percorso completo del file del documento diviso per indice con estensione predefinita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice del documento diviso. |
| estensione | java.lang.String | Estensione del file. |

**Returns:**
java.lang.String - Il percorso completo del file.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory per creare o rilasciare lo stream di anteprima della pagina di output.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
