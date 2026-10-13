---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Παρέχει επιλογές για το διαχωρισμό κειμένου του εγγράφου."
type: docs
weight: 41
url: /el/java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Παρέχει επιλογές για το διαχωρισμό κειμένου του εγγράφου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMode()](#getMode--) | Λειτουργία για διαίρεση κειμένου. |
| [getLineNumbers()](#getLineNumbers--) | Αριθμοί γραμμών για διαίρεση κειμένου. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Επικυρώνει τις επιλογές διαχωρισμού. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου κατά δείκτη με ορισμένη επέκταση. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory για δημιουργία ή απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| lineNumbers | int[] | Αριθμοί γραμμών για διαίρεση κειμένου. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mode | int | Λειτουργία για διαίρεση κειμένου. |
| lineNumbers | int[] | Αριθμοί γραμμών για διαίρεση κειμένου. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη καθορισμένη επέκταση. |
| lineNumbers | int[] | Αριθμοί γραμμών για διαίρεση κειμένου. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη καθορισμένη επέκταση. |
| mode | int | Λειτουργία για διαίρεση κειμένου. |
| lineNumbers | int[] | Αριθμοί γραμμών για διαίρεση κειμένου. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| lineNumbers | int[] | Αριθμοί γραμμών για διαίρεση κειμένου. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| mode | int | Λειτουργία για διαίρεση κειμένου. |
| lineNumbers | int[] | Αριθμοί γραμμών για διαίρεση κειμένου. |

### getMode() {#getMode--}
```
public final int getMode()
```


Λειτουργία για διαίρεση κειμένου.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Αριθμοί γραμμών για διαίρεση κειμένου.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Επικυρώνει τις επιλογές διαχωρισμού.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος αρχείου της κλάσης [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου κατά δείκτη με ορισμένη επέκταση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | Δείκτης του διαχωρισμένου εγγράφου. |
| επέκταση | java.lang.String | Επέκταση αρχείου. |

**Returns:**
java.lang.String - Η πλήρης διαδρομή αρχείου.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory για δημιουργία ή απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
