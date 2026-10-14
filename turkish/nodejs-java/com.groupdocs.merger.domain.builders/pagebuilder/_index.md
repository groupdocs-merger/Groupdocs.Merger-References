---
title: "PageBuilder"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Belgelerden sayfa koleksiyonunu almak için PageInfo oluşturucusu."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

Belgelerden sayfa koleksiyonunu almak için PageInfo oluşturucusu.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Yeni bir [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) sınıfının bir örneğini başlatır. |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Yeni bir [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOptions()](#getOptions--) | Sayfa oluşturucu seçenekleri. |
| [getPages()](#getPages--) | Sayfa koleksiyonu. |
| [getDocuments()](#getDocuments--) | Belge koleksiyonu. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Belgeyi belge koleksiyonuna ekle. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Belgeyi belge koleksiyonuna ekle. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Sayfayı sayfa koleksiyonuna ekle. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Sayfayı sayfa koleksiyonuna ekle. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Sayfaları sayfa koleksiyonuna ekle. |
| [clear()](#clear--) | Dahili koleksiyonları temizle. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Yeni bir [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) sınıfının bir örneğini başlatır.

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Yeni bir [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Sayfa oluşturucu seçenekleri. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Sayfa oluşturucu seçenekleri.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Sayfa koleksiyonu.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


Belge koleksiyonu.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Belgeyi belge koleksiyonuna ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | DocumentInfo indeksi. |
| akış | java.io.InputStream | DocumentInfo akışı. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo türü. |
| parola | java.lang.String | DocumentInfo parolası. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Belgeyi belge koleksiyonuna ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo örneği. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Sayfayı sayfa koleksiyonuna ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| documentIndex | int | DocumentInfo indeksi. |
| pageNumber | int | PageInfo numarası. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Sayfayı sayfa koleksiyonuna ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo örneği. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Sayfaları sayfa koleksiyonuna ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages dizisi. |

### clear() {#clear--}
```
public final void clear()
```


Dahili koleksiyonları temizle.

