---
title: "ISplitOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Διεπαφή για τις επιλογές διαχωρισμού."
type: docs
weight: 33
url: /el/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Διεπαφή για τις επιλογές διαχωρισμού.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMode()](#getMode--) | Λαμβάνει τη λειτουργία για το διαχωρισμό σελίδων. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Επικυρώνει τις επιλογές διαχωρισμού. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου κατά δείκτη με ορισμένη επέκταση. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Αντιπρόσωπος που ορίζει μέθοδο για δημιουργία ροής εξόδου διαίρεσης. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Λαμβάνει τη λειτουργία για το διαχωρισμό σελίδων.

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

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Αντιπρόσωπος που ορίζει μέθοδο για δημιουργία ροής εξόδου διαίρεσης.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
