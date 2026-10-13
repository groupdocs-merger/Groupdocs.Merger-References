---
title: "PageBuilder"
second_title: "Riferimento API di GroupDocs.Merger per Java"
description: "Builder PageInfo per ottenere la raccolta di pagine dai documenti."
type: docs
weight: 10
url: /it/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

Builder PageInfo per ottenere la raccolta di pagine dai documenti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Inizializza una nuova istanza della classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Inizializza una nuova istanza della classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOptions()](#getOptions--) | Le opzioni del costruttore di pagina. |
| [getPages()](#getPages--) | La collezione di pagine. |
| [getDocuments()](#getDocuments--) | La collezione di documenti. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Aggiungi documento alla collezione di documenti. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Aggiungi documento alla collezione di documenti. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Aggiungi pagina alla collezione di pagine. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Aggiungi pagina alla collezione di pagine. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Aggiungi pagine alla collezione di pagine. |
| [clear()](#clear--) | Cancella le collezioni interne. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Inizializza una nuova istanza della classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Inizializza una nuova istanza della classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Le opzioni del costruttore di pagina. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Le opzioni del costruttore di pagina.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


La collezione di pagine.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


La collezione di documenti.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Aggiungi documento alla collezione di documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | DocumentInfo indice. |
| stream | java.io.InputStream | DocumentInfo flusso. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo tipo. |
| password | java.lang.String | DocumentInfo password. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Aggiungi documento alla collezione di documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo istanza. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Aggiungi pagina alla collezione di pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentIndex | int | DocumentInfo indice. |
| pageNumber | int | PageInfo numero. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Aggiungi pagina alla collezione di pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo istanza. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Aggiungi pagine alla collezione di pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages array. |

### clear() {#clear--}
```
public final void clear()
```


Cancella le collezioni interne.

