---
title: "IOleWordProcessingOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου σε Επεξεργασία Κειμένου μέσω OLE."
type: docs
weight: 20
url: /el/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Διεπαφή για επιλογές εισαγωγής του ενσωματωμένου εγγράφου σε Επεξεργασία Κειμένου μέσω OLE.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLeft()](#getLeft--) | Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [setLeft(int value)](#setLeft-int-) | Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [getTop()](#getTop--) | Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [setTop(int value)](#setTop-int-) | Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [getImageData()](#getImageData--) | Τα δεδομένα της εικόνας του αντικειμένου Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole.

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
