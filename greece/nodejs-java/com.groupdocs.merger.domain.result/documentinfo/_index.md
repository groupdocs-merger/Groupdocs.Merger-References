---
title: "DocumentInfo"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Ορίζει ιδιότητες περιγραφής εγγράφου."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Ορίζει ιδιότητες περιγραφής εγγράφου.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Αρχικοποιεί νέα παρουσία της κλάσης [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Αρχικοποιεί νέα παρουσία της κλάσης [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Αρχικοποιεί νέα παρουσία της κλάσης [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getIndex()](#getIndex--) | Ο δείκτης του εγγράφου. |
| [getStream()](#getStream--) | Η ροή εγγράφου. |
| [getPassword()](#getPassword--) | Ο κωδικός πρόσβασης του εγγράφου. |
| [getType()](#getType--) | Λαμβάνει τον τύπο αρχείου. |
| [getPages()](#getPages--) | Ορίζει τη συλλογή σελίδων του εγγράφου. |
| [getPageCount()](#getPageCount--) | Ο αριθμός σελίδων του εγγράφου. |
| [getSize()](#getSize--) | Μέγεθος εγγράφου σε bytes |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Αρχικοποιεί νέα παρουσία της κλάσης [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |
| ροή | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου. |
| κωδικός | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Αρχικοποιεί νέα παρουσία της κλάσης [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |
| ροή | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου. |
| κωδικός | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Η λίστα σελίδων προς προβολή. |
| μέγεθος | long | Το μέγεθος του αρχείου. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Αρχικοποιεί νέα παρουσία της κλάσης [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Ο τύπος του αρχείου. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Η λίστα σελίδων προς προβολή. |
| μέγεθος | long | Το μέγεθος του αρχείου. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Ο δείκτης του εγγράφου.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Η ροή εγγράφου.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ο κωδικός πρόσβασης του εγγράφου.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Λαμβάνει τον τύπο αρχείου.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Ορίζει τη συλλογή σελίδων του εγγράφου.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Ο αριθμός σελίδων του εγγράφου.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Μέγεθος εγγράφου σε bytes

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.
