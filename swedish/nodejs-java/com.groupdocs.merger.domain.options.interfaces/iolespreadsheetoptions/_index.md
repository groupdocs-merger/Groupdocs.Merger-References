---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Gränssnitt för importalternativ för det inbäddade dokumentet till Kalkylblad via OLE."
type: docs
weight: 19
url: /sv/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Gränssnitt för importalternativ för det inbäddade dokumentet till Kalkylblad via OLE.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Det övre vänstra radindexet. |
| [setRowIndex(int value)](#setRowIndex-int-) | Det övre vänstra radindexet. |
| [getColumnIndex()](#getColumnIndex--) | Det övre vänstra kolumnindexet. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Det övre vänstra kolumnindexet. |
| [getImageData()](#getImageData--) | Data för Ole-objektets bild. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Det övre vänstra radindexet.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Det övre vänstra radindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Det övre vänstra kolumnindexet.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Det övre vänstra kolumnindexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Data för Ole-objektets bild.

**Returns:**
byte[]
