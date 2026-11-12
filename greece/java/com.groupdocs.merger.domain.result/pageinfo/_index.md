---
title: "PageInfo"
second_title: "GroupDocs.Merger για Java API Reference"
description: "Ορίζει ιδιότητες περιγραφής σελίδας."
type: docs
weight: 11
url: /el/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Ορίζει ιδιότητες περιγραφής σελίδας.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDocument()](#getDocument--) | Λαμβάνει τις πληροφορίες του εγγράφου. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Λαμβάνει τις πληροφορίες του εγγράφου. |
| [getNumber()](#getNumber--) | Λαμβάνει τον αριθμό σελίδας. |
| [getVisible()](#getVisible--) | Υποδεικνύει αν η σελίδα είναι ορατή ή όχι. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος της σελίδας σε εικονοστοιχεία όταν μετατρέπεται σε εικόνα. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος της σελίδας σε εικονοστοιχεία όταν μετατρέπεται σε εικόνα. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριθμός | int | Ο αριθμός σελίδας. |
| ορατό | boolean | Ο δείκτης ορατότητας της σελίδας. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αριθμός | int | Ο αριθμός σελίδας. |
| ορατό | boolean | Ο δείκτης ορατότητας της σελίδας. |
| πλάτος | int | Το πλάτος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |
| ύψος | int | Το ύψος της σελίδας σε εικονοστοιχεία όταν προβάλλεται ως JPG ή PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Λαμβάνει τις πληροφορίες του εγγράφου.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Λαμβάνει τις πληροφορίες του εγγράφου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Λαμβάνει τον αριθμό σελίδας.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Υποδεικνύει αν η σελίδα είναι ορατή ή όχι.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος της σελίδας σε εικονοστοιχεία όταν μετατρέπεται σε εικόνα.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος της σελίδας σε εικονοστοιχεία όταν μετατρέπεται σε εικόνα.

**Returns:**
int
