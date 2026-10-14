---
title: "PageBuilder"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "com.groupdocs.merger.licensing.metered"
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

com.groupdocs.merger.licensing.metered
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Initialiseert een nieuw exemplaar van de [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) klasse. |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Initialiseert een nieuw exemplaar van de [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getOptions()](#getOptions--) | De opties van de paginabouwer. |
| [getPages()](#getPages--) | De paginaverzameling. |
| [getDocuments()](#getDocuments--) | De documentverzameling. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Voeg document toe aan de documentverzameling. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Voeg document toe aan de documentverzameling. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Voeg pagina toe aan de paginaverzameling. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Voeg pagina toe aan de paginaverzameling. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Voeg pagina's toe aan de paginaverzameling. |
| [clear()](#clear--) | Maak de interne verzamelingen leeg. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Initialiseert een nieuw exemplaar van de [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) klasse.

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Initialiseert een nieuw exemplaar van de [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | De opties van de paginabouwer. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


De opties van de paginabouwer.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


De paginaverzameling.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


De documentverzameling.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Voeg document toe aan de documentverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | DocumentInfo index. |
| stream | java.io.InputStream | DocumentInfo stream. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo type. |
| password | java.lang.String | DocumentInfo password. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Voeg document toe aan de documentverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo instantie. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Voeg pagina toe aan de paginaverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentIndex | int | DocumentInfo index. |
| pageNumber | int | PageInfo nummer. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Voeg pagina toe aan de paginaverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo instantie. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Voeg pagina's toe aan de paginaverzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages-array. |

### clear() {#clear--}
```
public final void clear()
```


Maak de interne verzamelingen leeg.

