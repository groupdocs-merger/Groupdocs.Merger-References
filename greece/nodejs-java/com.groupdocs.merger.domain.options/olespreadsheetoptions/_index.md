---
title: "OleSpreadsheetOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στο Φύλλο Εργασίας μέσω OLE."
type: docs
weight: 20
url: /el/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στο Φύλλο Εργασίας μέσω OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Ο δείκτης της άνω αριστερής γραμμής. |
| [setRowIndex(int value)](#setRowIndex-int-) | Ο δείκτης της άνω αριστερής γραμμής. |
| [getColumnIndex()](#getColumnIndex--) | Ο δείκτης της άνω αριστερής στήλης. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Ο δείκτης της άνω αριστερής στήλης. |
| [getWidth()](#getWidth--) | Το πλάτος της εικόνας του αντικειμένου Ole. |
| [setWidth(int value)](#setWidth-int-) | Το πλάτος της εικόνας του αντικειμένου Ole. |
| [getHeight()](#getHeight--) | Το ύψος της εικόνας του αντικειμένου Ole. |
| [setHeight(int value)](#setHeight-int-) | Το ύψος της εικόνας του αντικειμένου Ole. |
| [getImageData()](#getImageData--) | Τα δεδομένα της εικόνας του αντικειμένου Ole. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objectData | byte[] | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| imageData | byte[] | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
| επέκταση | java.lang.String | Η επέκταση του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| imageData | byte[] | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


Ο δείκτης της άνω αριστερής γραμμής.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


Ο δείκτης της άνω αριστερής γραμμής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


Ο δείκτης της άνω αριστερής στήλης.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


Ο δείκτης της άνω αριστερής στήλης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Το πλάτος της εικόνας του αντικειμένου Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Το πλάτος της εικόνας του αντικειμένου Ole.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Το ύψος της εικόνας του αντικειμένου Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Το ύψος της εικόνας του αντικειμένου Ole.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Τα δεδομένα της εικόνας του αντικειμένου Ole.

**Returns:**
byte[]
