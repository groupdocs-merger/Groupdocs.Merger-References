---
title: "PreviewOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Αναπαριστά τις επιλογές προεπισκόπησης εγγράφου."
type: docs
weight: 29
url: /el/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Αναπαριστά τις επιλογές προεπισκόπησης εγγράφου.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWidth()](#getWidth--) | Πλάτος προεπισκόπησης. |
| [setWidth(int value)](#setWidth-int-) | Πλάτος προεπισκόπησης. |
| [getHeight()](#getHeight--) | Ύψος προεπισκόπησης. |
| [setHeight(int value)](#setHeight-int-) | Ύψος προεπισκόπησης. |
| [getResolution()](#getResolution--) | Ανάλυση εικόνας. |
| [setResolution(int value)](#setResolution-int-) | Ανάλυση εικόνας. |
| [getMode()](#getMode--) | Λειτουργία για προεπισκόπηση. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Επικυρώνει τις επιλογές προεπισκόπησης. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Λαμβάνει τη πλήρη διαδρομή αρχείου του προεπισκοπούμενου εγγράφου με βάση τον αριθμό σελίδας και με ορισμένη επέκταση. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory για δημιουργία ή απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| previewMode | int | Η λειτουργία προεπισκόπησης του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| previewMode | int | Η λειτουργία προεπισκόπησης του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Αριθμοί σελίδων. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| previewMode | int | Η λειτουργία προεπισκόπησης του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Ο αριθμός εκκίνησης σελίδας. |
| endNumber | int | Ο αριθμός λήξης σελίδας. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων εξόδου σελίδας. |
| previewMode | int | Η λειτουργία προεπισκόπησης του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Ο αριθμός εκκίνησης σελίδας. |
| endNumber | int | Ο αριθμός λήξης σελίδας. |
| mode | int | Η λειτουργία εύρους. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Πλάτος προεπισκόπησης.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Πλάτος προεπισκόπησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ύψος προεπισκόπησης.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ύψος προεπισκόπησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Ανάλυση εικόνας.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Ανάλυση εικόνας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Λειτουργία για προεπισκόπηση.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Επικυρώνει τις επιλογές προεπισκόπησης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος αρχείου. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Λαμβάνει τη πλήρη διαδρομή αρχείου του προεπισκοπούμενου εγγράφου με βάση τον αριθμό σελίδας και με ορισμένη επέκταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageNumber | int | Αριθμός σελίδας προεπισκόπησης. |
| επέκταση | java.lang.String | Επέκταση αρχείου. |

**Returns:**
java.lang.String - Η πλήρης διαδρομή αρχείου.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory για δημιουργία ή απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
