---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στην Επεξεργασία Κειμένου μέσω OLE."
type: docs
weight: 21
url: /el/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Παρέχει επιλογές για την εισαγωγή του ενσωματωμένου εγγράφου στην Επεξεργασία Κειμένου μέσω OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLeft()](#getLeft--) | Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [setLeft(int value)](#setLeft-int-) | Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [getTop()](#getTop--) | Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [setTop(int value)](#setTop-int-) | Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole. |
| [getWidth()](#getWidth--) | Το πλάτος της εικόνας του αντικειμένου Ole. |
| [setWidth(int value)](#setWidth-int-) | Το πλάτος της εικόνας του αντικειμένου Ole. |
| [getHeight()](#getHeight--) | Το ύψος της εικόνας του αντικειμένου Ole. |
| [setHeight(int value)](#setHeight-int-) | Το ύψος της εικόνας του αντικειμένου Ole. |
| [getImageData()](#getImageData--) | Τα δεδομένα της εικόνας του αντικειμένου Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objectData | byte[] | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| imageData | byte[] | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
| επέκταση | java.lang.String | Η επέκταση του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| imageData | byte[] | Τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Η αριστερή συντεταγμένη της εικόνας του αντικειμένου Ole.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Η άνω συντεταγμένη της εικόνας του αντικειμένου Ole.

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
