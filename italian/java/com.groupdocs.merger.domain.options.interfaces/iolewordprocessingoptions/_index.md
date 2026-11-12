---
title: "IOleWordProcessingOptions"
second_title: "Riferimento API di GroupDocs.Merger per Java"
description: "Interfaccia per le opzioni di importazione del documento incorporato in Elaborazione testi tramite OLE."
type: docs
weight: 20
url: /it/java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Interfaccia per le opzioni di importazione del documento incorporato in Elaborazione testi tramite OLE.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLeft()](#getLeft--) | La coordinata sinistra dell'immagine dell'oggetto Ole. |
| [setLeft(int value)](#setLeft-int-) | La coordinata sinistra dell'immagine dell'oggetto Ole. |
| [getTop()](#getTop--) | La coordinata superiore dell'immagine dell'oggetto Ole. |
| [setTop(int value)](#setTop-int-) | La coordinata superiore dell'immagine dell'oggetto Ole. |
| [getImageData()](#getImageData--) | I dati dell'immagine dell'oggetto Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


La coordinata sinistra dell'immagine dell'oggetto Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


La coordinata sinistra dell'immagine dell'oggetto Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


La coordinata superiore dell'immagine dell'oggetto Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


La coordinata superiore dell'immagine dell'oggetto Ole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


I dati dell'immagine dell'oggetto Ole.

**Returns:**
byte[]
