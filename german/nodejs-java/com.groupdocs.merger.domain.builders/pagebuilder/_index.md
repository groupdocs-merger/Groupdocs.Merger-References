---
title: "PageBuilder"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "PageInfo builder zum Abrufen der Seitensammlung aus den Dokumenten."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

PageInfo builder zum Abrufen der Seitensammlung aus den Dokumenten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Initialisiert eine neue Instanz der [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder)-Klasse. |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Initialisiert eine neue Instanz der [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOptions()](#getOptions--) | Die Optionen des Page-Builders. |
| [getPages()](#getPages--) | Die Seitensammlung. |
| [getDocuments()](#getDocuments--) | Die Dokumentsammlung. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Dokument zur Dokumentsammlung hinzufügen. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Dokument zur Dokumentsammlung hinzufügen. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Seite zur Seitensammlung hinzufügen. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Seite zur Seitensammlung hinzufügen. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Seiten zur Seitensammlung hinzufügen. |
| [clear()](#clear--) | Interne Sammlungen leeren. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Initialisiert eine neue Instanz der [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder)-Klasse.

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Initialisiert eine neue Instanz der [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder)-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Die Optionen des Page-Builders. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Die Optionen des Page-Builders.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Die Seitensammlung.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


Die Dokumentsammlung.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Dokument zur Dokumentsammlung hinzufügen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | DocumentInfo-Index. |
| Stream | java.io.InputStream | DocumentInfo-Stream. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo-Typ. |
| Passwort | java.lang.String | DocumentInfo-Passwort. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Dokument zur Dokumentsammlung hinzufügen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo-Instanz. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Seite zur Seitensammlung hinzufügen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentIndex | int | DocumentInfo-Index. |
| pageNumber | int | PageInfo-Nummer. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Seite zur Seitensammlung hinzufügen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo-Instanz. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Seiten zur Seitensammlung hinzufügen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages-Array. |

### clear() {#clear--}
```
public final void clear()
```


Interne Sammlungen leeren.

