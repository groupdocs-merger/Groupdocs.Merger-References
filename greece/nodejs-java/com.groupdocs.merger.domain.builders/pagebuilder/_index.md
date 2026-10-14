---
title: "PageBuilder"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Κατασκευαστής PageInfo για την λήψη της συλλογής σελίδων από τα έγγραφα."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

Κατασκευαστής PageInfo για την λήψη της συλλογής σελίδων από τα έγγραφα.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getOptions()](#getOptions--) | Οι επιλογές του δημιουργού σελίδων. |
| [getPages()](#getPages--) | Η συλλογή σελίδων. |
| [getDocuments()](#getDocuments--) | Η συλλογή εγγράφων. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Προσθέστε το έγγραφο στη συλλογή εγγράφων. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Προσθέστε το έγγραφο στη συλλογή εγγράφων. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Προσθέστε τη σελίδα στη συλλογή σελίδων. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Προσθέστε τη σελίδα στη συλλογή σελίδων. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Προσθέστε σελίδες στη συλλογή σελίδων. |
| [clear()](#clear--) | Καθαρίστε τις εσωτερικές συλλογές. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Οι επιλογές του δημιουργού σελίδων. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Οι επιλογές του δημιουργού σελίδων.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Η συλλογή σελίδων.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


Η συλλογή εγγράφων.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Προσθέστε το έγγραφο στη συλλογή εγγράφων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int | DocumentInfo δείκτης. |
| ροή | java.io.InputStream | DocumentInfo ροή. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo τύπος. |
| κωδικός | java.lang.String | DocumentInfo κωδικός. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Προσθέστε το έγγραφο στη συλλογή εγγράφων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo αντίτυπο. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Προσθέστε τη σελίδα στη συλλογή σελίδων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentIndex | int | DocumentInfo δείκτης. |
| pageNumber | int | PageInfo αριθμός. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Προσθέστε τη σελίδα στη συλλογή σελίδων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo αντίγραφο. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Προσθέστε σελίδες στη συλλογή σελίδων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages πίνακας. |

### clear() {#clear--}
```
public final void clear()
```


Καθαρίστε τις εσωτερικές συλλογές.

