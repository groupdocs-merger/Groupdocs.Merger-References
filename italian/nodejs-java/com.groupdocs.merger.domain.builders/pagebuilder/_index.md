---
title: "PageBuilder"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "com.groupdocs.merger.licensing.metered"
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

com.groupdocs.merger.licensing.metered
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Inizializza una nuova istanza della classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Inizializza una nuova istanza della classe [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOptions()](#getOptions--) | Le opzioni del page builder. |
| [getPages()](#getPages--) | La collezione di pagine. |
| [getDocuments()](#getDocuments--) | La collezione di documenti. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Aggiungi il documento alla collezione di documenti. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Aggiungi il documento alla collezione di documenti. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Aggiungi la pagina alla collezione di pagine. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Aggiungi la pagina alla collezione di pagine. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Aggiungi le pagine alla collezione di pagine. |
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
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Le opzioni del page builder. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Le opzioni del page builder.

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


Aggiungi il documento alla collezione di documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | Indice DocumentInfo. |
| flusso | java.io.InputStream | Flusso DocumentInfo. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipo DocumentInfo. |
| password | java.lang.String | Password DocumentInfo. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Aggiungi il documento alla collezione di documenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | Istanza DocumentInfo. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Aggiungi la pagina alla collezione di pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentIndex | int | Indice DocumentInfo. |
| pageNumber | int | Numero di PageInfo. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Aggiungi la pagina alla collezione di pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | Istanza di PageInfo. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Aggiungi le pagine alla collezione di pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Array di Pages. |

### clear() {#clear--}
```
public final void clear()
```


Cancella le collezioni interne.

