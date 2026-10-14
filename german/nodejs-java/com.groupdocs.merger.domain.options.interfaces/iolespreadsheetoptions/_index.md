---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für Importoptionen des eingebetteten Dokuments zu Tabellenkalkulation via OLE."
type: docs
weight: 19
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Schnittstelle für Importoptionen des eingebetteten Dokuments zu Tabellenkalkulation via OLE.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Der Index der oberen linken Zeile. |
| [setRowIndex(int value)](#setRowIndex-int-) | Der Index der oberen linken Zeile. |
| [getColumnIndex()](#getColumnIndex--) | Der Index der oberen linken Spalte. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Der Index der oberen linken Spalte. |
| [getImageData()](#getImageData--) | Die Daten des Ole-Objektbildes. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Der Index der oberen linken Zeile.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Der Index der oberen linken Zeile.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Der Index der oberen linken Spalte.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Der Index der oberen linken Spalte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Die Daten des Ole-Objektbildes.

**Returns:**
byte[]
