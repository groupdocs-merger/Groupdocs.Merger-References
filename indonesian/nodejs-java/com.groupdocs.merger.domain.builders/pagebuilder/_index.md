---
title: "PageBuilder"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Builder PageInfo untuk mendapatkan koleksi halaman dari dokumen."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

Builder PageInfo untuk mendapatkan koleksi halaman dari dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Menginisialisasi instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Menginisialisasi instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOptions()](#getOptions--) | Opsi pembuat halaman. |
| [getPages()](#getPages--) | Koleksi halaman. |
| [getDocuments()](#getDocuments--) | Koleksi dokumen. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Tambahkan dokumen ke koleksi dokumen. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Tambahkan dokumen ke koleksi dokumen. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Tambahkan halaman ke koleksi halaman. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Tambahkan halaman ke koleksi halaman. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Tambahkan beberapa halaman ke koleksi halaman. |
| [clear()](#clear--) | Bersihkan koleksi internal. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Menginisialisasi instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Menginisialisasi instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Opsi pembuat halaman. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Opsi pembuat halaman.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Koleksi halaman.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


Koleksi dokumen.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Tambahkan dokumen ke koleksi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | DocumentInfo indeks. |
| stream | java.io.InputStream | DocumentInfo aliran. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo tipe. |
| kata sandi | java.lang.String | DocumentInfo kata sandi. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Tambahkan dokumen ke koleksi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo instance. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Tambahkan halaman ke koleksi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentIndex | int | DocumentInfo indeks. |
| pageNumber | int | Nomor PageInfo. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Tambahkan halaman ke koleksi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | Instansi PageInfo. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Tambahkan beberapa halaman ke koleksi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Array Pages. |

### clear() {#clear--}
```
public final void clear()
```


Bersihkan koleksi internal.

