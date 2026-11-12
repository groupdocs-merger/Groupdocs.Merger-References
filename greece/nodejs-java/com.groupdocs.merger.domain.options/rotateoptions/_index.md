---
title: "RotateOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για την περιστροφή της σελίδας."
type: docs
weight: 33
url: /el/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Παρέχει επιλογές για την περιστροφή της σελίδας.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης. |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMode()](#getMode--) | Λαμβάνει τη λειτουργία για περιστροφή (90, 180 ή 270 μοίρες). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateMode | int | Η λειτουργία περιστροφής του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateMode | int | Η λειτουργία περιστροφής του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Αριθμοί σελίδων. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateMode | int | Η λειτουργία περιστροφής του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Ο αριθμός εκκίνησης σελίδας. |
| endNumber | int | Ο αριθμός λήξης σελίδας. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Αρχικοποιεί μια νέα παρουσία της [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) κλάσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rotateMode | int | Η λειτουργία περιστροφής του Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Ο αριθμός εκκίνησης σελίδας. |
| endNumber | int | Ο αριθμός λήξης σελίδας. |
| mode | int | Η λειτουργία εύρους. |

### getMode() {#getMode--}
```
public final int getMode()
```


Λαμβάνει τη λειτουργία για περιστροφή (90, 180 ή 270 μοίρες).

**Returns:**
int
