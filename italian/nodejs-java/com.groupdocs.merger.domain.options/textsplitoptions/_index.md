---
title: "TextSplitOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per la divisione del testo del documento."
type: docs
weight: 39
url: /it/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Fornisce opzioni per la divisione del testo del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMode()](#getMode--) | Modalità per la divisione del testo. |
| [getLineNumbers()](#getLineNumbers--) | Numeri di riga per la divisione del testo. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Convalida le opzioni di divisione. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ottiene il percorso completo del file del documento diviso per indice con estensione definita. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory per creare o rilasciare lo stream di anteprima della pagina di output. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lineNumbers | int[] | Numeri di riga per la divisione del testo. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | int | Modalità per la divisione del testo. |
| lineNumbers | int[] | Numeri di riga per la divisione del testo. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già definita. |
| lineNumbers | int[] | Numeri di riga per la divisione del testo. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePathFormat | java.lang.String | Il formato del percorso file, ad es. 'c:/split\{0\}.doc' o 'c:/split\{0\}.\{1\}' con estensione già definita. |
| mode | int | Modalità per la divisione del testo. |
| lineNumbers | int[] | Numeri di riga per la divisione del testo. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| lineNumbers | int[] | Numeri di riga per la divisione del testo. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Inizializza una nuova istanza della classe [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Il metodo che istanzia lo stream utilizzato per scrivere i dati di divisione dell'output. |
| mode | int | Modalità per la divisione del testo. |
| lineNumbers | int[] | Numeri di riga per la divisione del testo. |

### getMode() {#getMode--}
```
public final int getMode()
```


Modalità per la divisione del testo.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Numeri di riga per la divisione del testo.

**Returns:**
int[]
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


Ottiene il percorso completo del file del documento diviso per indice con estensione definita.

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
