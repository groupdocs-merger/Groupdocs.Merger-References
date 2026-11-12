---
title: "PageBuilder"
second_title: "L'espace de noms com.groupdocs.merger.domain.builders fournit des constructeurs."
description: "com.groupdocs.merger.licensing.metered"
type: docs
weight: 10
url: /fr/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

com.groupdocs.merger.licensing.metered
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Initialise une nouvelle instance de la classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Initialise une nouvelle instance de la classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOptions()](#getOptions--) | Les options du constructeur de page. |
| [getPages()](#getPages--) | La collection de pages. |
| [getDocuments()](#getDocuments--) | La collection de documents. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Ajouter un document à la collection de documents. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Ajouter un document à la collection de documents. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Ajouter une page à la collection de pages. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Ajouter une page à la collection de pages. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Ajouter des pages à la collection de pages. |
| [clear()](#clear--) | Effacer les collections internes. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Initialise une nouvelle instance de la classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Initialise une nouvelle instance de la classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Les options du constructeur de page. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Les options du constructeur de page.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


La collection de pages.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


La collection de documents.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Ajouter un document à la collection de documents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | DocumentInfo indice. |
| flux | java.io.InputStream | DocumentInfo flux. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo type. |
| mot de passe | java.lang.String | DocumentInfo password. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Ajouter un document à la collection de documents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo instance. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Ajouter une page à la collection de pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentIndex | int | DocumentInfo indice. |
| pageNumber | int | PageInfo numéro. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Ajouter une page à la collection de pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo instance. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Ajouter des pages à la collection de pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages tableau. |

### clear() {#clear--}
```
public final void clear()
```


Effacer les collections internes.

