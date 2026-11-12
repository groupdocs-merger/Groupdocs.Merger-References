---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου σε Φύλλο Εργασίας μέσω OLE."
type: docs
weight: 19
url: /el/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου σε Φύλλο Εργασίας μέσω OLE.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Ο δείκτης της άνω αριστερής γραμμής. |
| [setRowIndex(int value)](#setRowIndex-int-) | Ο δείκτης της άνω αριστερής γραμμής. |
| [getColumnIndex()](#getColumnIndex--) | Ο δείκτης της άνω αριστερής στήλης. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Ο δείκτης της άνω αριστερής στήλης. |
| [getImageData()](#getImageData--) | Τα δεδομένα της εικόνας του αντικειμένου Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Ο δείκτης της άνω αριστερής γραμμής.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Ο δείκτης της άνω αριστερής γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Ο δείκτης της άνω αριστερής στήλης.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Ο δείκτης της άνω αριστερής στήλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Τα δεδομένα της εικόνας του αντικειμένου Ole.

**Returns:**
byte[]
