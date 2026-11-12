---
title: "SplitOptions"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Παρέχει επιλογές για το διαχωρισμό σελίδων του εγγράφου."
type: docs
weight: 38
url: /el/java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Παρέχει επιλογές για το διαχωρισμό σελίδων του εγγράφου.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMode()](#getMode--) | Λαμβάνει τη λειτουργία για το διαχωρισμό σελίδων. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Επικυρώνει τις επιλογές διαχωρισμού. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου με βάση το δείκτη και με προ-ορισμένη επέκταση. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory για δημιουργία ή απελευθέρωση ροής προεπισκόπησης εξόδου σελίδας. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageNumbers | int[] | Αριθμοί σελίδων. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |
| mode | int | Η λειτουργία εύρους. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη προ-ορισμένη επέκταση. |
| pageNumbers | int[] | Αριθμοί σελίδων. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη προ-ορισμένη επέκταση. |
| pageNumbers | int[] | Αριθμοί σελίδων. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη προ-ορισμένη επέκταση. |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη προ-ορισμένη επέκταση. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη προ-ορισμένη επέκταση. |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |
| mode | java.lang.Integer | Η λειτουργία εύρους. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | java.lang.String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split\{0\}.doc' ή 'c:/split\{0\}.\{1\}' με ήδη προ-ορισμένη επέκταση. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |
| mode | int | Η λειτουργία εύρους. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| pageNumbers | int[] | Αριθμοί σελίδων. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| pageNumbers | int[] | Αριθμοί σελίδων. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |
| mode | java.lang.Integer | Η λειτουργία εύρους. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των διαχωρισμένων δεδομένων εξόδου. |
| splitMode | int | Η λειτουργία διαχωρισμού του Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Ο αριθμός της αρχικής σελίδας. |
| endNumber | int | Ο αριθμός της τελικής σελίδας. |
| mode | int | Η λειτουργία εύρους. |

### getMode() {#getMode--}
```
public final int getMode()
```


Λαμβάνει τη λειτουργία για το διαχωρισμό σελίδων.

**Returns:**
int
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


Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου με βάση το δείκτη και με προ-ορισμένη επέκταση.

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
