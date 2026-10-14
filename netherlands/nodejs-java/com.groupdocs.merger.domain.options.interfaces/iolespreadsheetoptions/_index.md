---
title: "IOleSpreadsheetOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor importopties van het ingesloten document naar Spreadsheet via OLE."
type: docs
weight: 19
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Interface voor importopties van het ingesloten document naar Spreadsheet via OLE.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | De index van de bovenste linker rij. |
| [setRowIndex(int value)](#setRowIndex-int-) | De index van de bovenste linker rij. |
| [getColumnIndex()](#getColumnIndex--) | De index van de bovenste linker kolom. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | De index van de bovenste linker kolom. |
| [getImageData()](#getImageData--) | De gegevens van de Ole‑objectafbeelding. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


De index van de bovenste linker rij.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


De index van de bovenste linker rij.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


De index van de bovenste linker kolom.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


De index van de bovenste linker kolom.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


De gegevens van de Ole‑objectafbeelding.

**Returns:**
byte[]
