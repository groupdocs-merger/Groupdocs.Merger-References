---
title: "IOleSpreadsheetOptions"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου στο Spreadsheet μέσω OLE."
type: docs
weight: 19
url: /el/java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου στο Spreadsheet μέσω OLE.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Ο δείκτης γραμμής επάνω αριστερά. |
| [setRowIndex(int value)](#setRowIndex-int-) | Ο δείκτης γραμμής επάνω αριστερά. |
| [getColumnIndex()](#getColumnIndex--) | Ο δείκτης στήλης επάνω αριστερά. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Ο δείκτης στήλης επάνω αριστερά. |
| [getImageData()](#getImageData--) | Τα δεδομένα της εικόνας του αντικειμένου Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Ο δείκτης γραμμής επάνω αριστερά.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Ο δείκτης γραμμής επάνω αριστερά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Ο δείκτης στήλης επάνω αριστερά.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Ο δείκτης στήλης επάνω αριστερά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Τα δεδομένα της εικόνας του αντικειμένου Ole.

**Returns:**
byte[]
