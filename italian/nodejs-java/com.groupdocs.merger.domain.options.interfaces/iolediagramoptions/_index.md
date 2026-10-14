---
title: "IOleDiagramOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per le opzioni di importazione del documento incorporato in Diagram tramite OLE."
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Interfaccia per le opzioni di importazione del documento incorporato in Diagram tramite OLE.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getX()](#getX--) | La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [setX(int value)](#setX-int-) | La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [getY()](#getY--) | La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [setY(int value)](#setY-int-) | La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina. |
| [getImageData()](#getImageData--) | I dati dell'immagine dell'oggetto incorporato. |
### getX() {#getX--}
```
public abstract int getX()
```


La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


La coordinata X del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


La coordinata Y del perno della forma dell'oggetto incorporato (centro di rotazione) in relazione alla pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


I dati dell'immagine dell'oggetto incorporato.

**Returns:**
byte[]
