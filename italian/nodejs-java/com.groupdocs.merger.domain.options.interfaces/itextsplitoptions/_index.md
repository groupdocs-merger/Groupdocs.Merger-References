---
title: "ITextSplitOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per le opzioni di divisione del testo."
type: docs
weight: 35
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Interfaccia per le opzioni di divisione del testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Numeri di riga per la divisione del testo. |
| [getMode()](#getMode--) | Modalità per la divisione del testo. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Convalida le opzioni di divisione. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ottiene il percorso completo del file del documento diviso per indice con estensione definita. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegato che definisce il metodo per creare lo stream di divisione dell'output. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Numeri di riga per la divisione del testo.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Modalità per la divisione del testo.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Convalida le opzioni di divisione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo di file della classe [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegato che definisce il metodo per creare lo stream di divisione dell'output.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
