---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Διεπαφή για τις επιλογές προεπισκόπησης."
type: docs
weight: 28
url: /el/java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Διεπαφή για τις επιλογές προεπισκόπησης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Πλάτος προεπισκόπησης. |
| [setWidth(int value)](#setWidth-int-) | Πλάτος προεπισκόπησης. |
| [getHeight()](#getHeight--) | Ύψος προεπισκόπησης. |
| [setHeight(int value)](#setHeight-int-) | Ύψος προεπισκόπησης. |
| [getResolution()](#getResolution--) | Ανάλυση εικόνας. |
| [setResolution(int value)](#setResolution-int-) | Ανάλυση εικόνας. |
| [getMode()](#getMode--) | Λαμβάνει τη λειτουργία προεπισκόπησης. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Επικυρώνει τις επιλογές διαχωρισμού. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Λαμβάνει τη πλήρη διαδρομή αρχείου του προεπισκοπούμενου εγγράφου ανά αριθμό σελίδας με καθορισμένη επέκταση. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegate που ορίζει τη μέθοδο για δημιουργία ροής προεπισκόπησης εξόδου σελίδας. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Πλάτος προεπισκόπησης.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Πλάτος προεπισκόπησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Ύψος προεπισκόπησης.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Ύψος προεπισκόπησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Ανάλυση εικόνας.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Ανάλυση εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Λαμβάνει τη λειτουργία προεπισκόπησης.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Επικυρώνει τις επιλογές διαχωρισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος αρχείου της κλάσης [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Λαμβάνει τη πλήρη διαδρομή αρχείου του προεπισκοπούμενου εγγράφου ανά αριθμό σελίδας με καθορισμένη επέκταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageNumber | int | Αριθμός σελίδας προεπισκόπησης. |
| επέκταση | java.lang.String | Επέκταση αρχείου. |

**Returns:**
java.lang.String - Η πλήρης διαδρομή αρχείου.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Delegate που ορίζει τη μέθοδο για δημιουργία ροής προεπισκόπησης εξόδου σελίδας.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
