---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Διεπαφή για τις επιλογές διαχωρισμού κειμένου."
type: docs
weight: 35
url: /el/java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Διεπαφή για τις επιλογές διαχωρισμού κειμένου.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Αριθμοί γραμμών για διαίρεση κειμένου. |
| [getMode()](#getMode--) | Λειτουργία για διαίρεση κειμένου. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Επικυρώνει τις επιλογές διαχωρισμού. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου κατά δείκτη με ορισμένη επέκταση. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate που ορίζει τη μέθοδο για τη δημιουργία ροής εξόδου διαχωρισμού. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Αριθμοί γραμμών για διαίρεση κειμένου.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Λειτουργία για διαίρεση κειμένου.

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


Delegate που ορίζει τη μέθοδο για τη δημιουργία ροής εξόδου διαχωρισμού.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
