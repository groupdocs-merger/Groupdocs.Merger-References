---
title: PageBuilder
second_title: GroupDocs.Merger for Node.js via Java API Reference
description: PageInfo builder for getting the page collection from the documents.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

PageInfo builder for getting the page collection from the documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Initializes a new instance of the [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) class. |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Initializes a new instance of the [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) class. |
## Methods

| Method | Description |
| --- | --- |
| [getOptions()](#getOptions--) | The page builder options. |
| [getPages()](#getPages--) | The page collection. |
| [getDocuments()](#getDocuments--) | The document collection. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Add document to the document collection. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Add document to the document collection. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Add page to the page collection. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Add page to the page collection. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Add pages to the page collection. |
| [clear()](#clear--) | Clear the internal collections. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Initializes a new instance of the [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) class.

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Initializes a new instance of the [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | The page builder options. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


The page builder options.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


The page collection.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


The document collection.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Add document to the document collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | DocumentInfo index. |
| stream | java.io.InputStream | DocumentInfo stream. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo type. |
| password | java.lang.String | DocumentInfo password. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Add document to the document collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo instance. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Add page to the page collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentIndex | int | DocumentInfo index. |
| pageNumber | int | PageInfo number. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Add page to the page collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo instance. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Add pages to the page collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages array. |

### clear() {#clear--}
```
public final void clear()
```


Clear the internal collections.

