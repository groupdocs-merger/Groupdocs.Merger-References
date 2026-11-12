---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Interface voor importopties van het ingesloten document naar Spreadsheet via OLE."
type: docs
weight: 19
url: /nl/java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
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
| [getRowIndex()](#getRowIndex--) | De bovenste linkse rij-index. |
| [setRowIndex(int value)](#setRowIndex-int-) | De bovenste linkse rij-index. |
| [getColumnIndex()](#getColumnIndex--) | De bovenste linkse kolom-index. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | De bovenste linkse kolom-index. |
| [getImageData()](#getImageData--) | De gegevens van de Ole-objectafbeelding. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


De bovenste linkse rij-index.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


De bovenste linkse rij-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


De bovenste linkse kolom-index.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


De bovenste linkse kolom-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


De gegevens van de Ole-objectafbeelding.

**Returns:**
byte[]
