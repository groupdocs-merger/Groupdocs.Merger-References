---
title: "IImportDocumentOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per l'importazione del documento incorporato."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Interfaccia per l'importazione del documento incorporato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectData()](#getObjectData--) | I dati dell'oggetto incorporato. |
| [getExtension()](#getExtension--) | L'estensione dell'oggetto incorporato. |
| [getPageNumber()](#getPageNumber--) | Il numero di pagina per l'inserimento dell'oggetto incorporato. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


I dati dell'oggetto incorporato.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


L'estensione dell'oggetto incorporato.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Il numero di pagina per l'inserimento dell'oggetto incorporato.

**Returns:**
int
