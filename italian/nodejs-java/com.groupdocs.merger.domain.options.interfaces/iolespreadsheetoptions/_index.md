---
title: "IOleSpreadsheetOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Interfaccia per le opzioni di importazione del documento incorporato in Spreadsheet tramite OLE."
type: docs
weight: 19
url: /it/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Interfaccia per le opzioni di importazione del documento incorporato in Spreadsheet tramite OLE.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | L'indice della riga in alto a sinistra. |
| [setRowIndex(int value)](#setRowIndex-int-) | L'indice della riga in alto a sinistra. |
| [getColumnIndex()](#getColumnIndex--) | L'indice della colonna in alto a sinistra. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | L'indice della colonna in alto a sinistra. |
| [getImageData()](#getImageData--) | I dati dell'immagine dell'oggetto Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


L'indice della riga in alto a sinistra.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


L'indice della riga in alto a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


L'indice della colonna in alto a sinistra.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


L'indice della colonna in alto a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


I dati dell'immagine dell'oggetto Ole.

**Returns:**
byte[]
