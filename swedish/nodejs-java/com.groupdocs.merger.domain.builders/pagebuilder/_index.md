---
title: "PageBuilder"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "PageInfo-byggare för att hämta sidkollektionen från dokumenten."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

PageInfo-byggare för att hämta sidkollektionen från dokumenten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Initierar en ny instans av klassen [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Initierar en ny instans av klassen [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOptions()](#getOptions--) | Alternativen för sidbyggaren. |
| [getPages()](#getPages--) | Sidsamlingen. |
| [getDocuments()](#getDocuments--) | Dokumentsamlingen. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Lägg till dokument i dokumentsamlingen. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Lägg till dokument i dokumentsamlingen. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Lägg till sida i sidsamlingen. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Lägg till sida i sidsamlingen. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Lägg till sidor i sidsamlingen. |
| [clear()](#clear--) | Rensa de interna samlingarna. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Initierar en ny instans av klassen [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Initierar en ny instans av klassen [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Alternativen för sidbyggaren. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Alternativen för sidbyggaren.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Sidsamlingen.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


Dokumentsamlingen.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Lägg till dokument i dokumentsamlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | DocumentInfo index. |
| ström | java.io.InputStream | DocumentInfo ström. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo typ. |
| lösenord | java.lang.String | DocumentInfo lösenord. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Lägg till dokument i dokumentsamlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo instans. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Lägg till sida i sidsamlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentIndex | int | DocumentInfo index. |
| pageNumber | int | PageInfo-nummer. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Lägg till sida i sidsamlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo-instans. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Lägg till sidor i sidsamlingen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages-array. |

### clear() {#clear--}
```
public final void clear()
```


Rensa de interna samlingarna.

