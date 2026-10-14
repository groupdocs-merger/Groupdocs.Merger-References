---
title: "OrientationOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για τον προσανατολισμό σελίδας."
type: docs
weight: 23
url: /el/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Παρέχει επιλογές για τον προσανατολισμό σελίδας.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getMode()](#getMode--) | Λαμβάνει τη λειτουργία για τον προσανατολισμό της σελίδας. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orientationMode | int | Η λειτουργία προσανατολισμού του [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orientationMode | int | Η λειτουργία προσανατολισμού του [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| pageNumbers | int[] | Αριθμοί σελίδων. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orientationMode | int | Η λειτουργία προσανατολισμού του [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Ο αριθμός εκκίνησης σελίδας. |
| endNumber | int | Ο αριθμός λήξης σελίδας. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| orientationMode | int | Η λειτουργία προσανατολισμού του [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Ο αριθμός εκκίνησης σελίδας. |
| endNumber | int | Ο αριθμός λήξης σελίδας. |
| mode | int | Η λειτουργία εύρους. |

### getMode() {#getMode--}
```
public final int getMode()
```


Λαμβάνει τη λειτουργία για τον προσανατολισμό της σελίδας.

**Returns:**
int
