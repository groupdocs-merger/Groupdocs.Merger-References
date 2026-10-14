---
title: "ISplitOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per le opzioni di divisione."
type: docs
weight: 33
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Interfaccia per le opzioni di divisione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMode()](#getMode--) | Ottiene la modalità per la divisione delle pagine. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Convalida le opzioni di divisione. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ottiene il percorso completo del file del documento diviso per indice con estensione definita. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegato che definisce il metodo per creare lo stream di divisione dell'output. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Ottiene la modalità per la divisione delle pagine.

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
