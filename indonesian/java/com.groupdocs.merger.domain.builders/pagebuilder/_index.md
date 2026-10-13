---
title: "PageBuilder"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Builder PageInfo untuk mendapatkan koleksi halaman dari dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

Builder PageInfo untuk mendapatkan koleksi halaman dari dokumen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Menginisialisasi sebuah instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Menginisialisasi sebuah instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
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
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Tambahkan halaman ke koleksi halaman. |
| [clear()](#clear--) | Bersihkan koleksi internal. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Menginisialisasi sebuah instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Menginisialisasi sebuah instance baru dari kelas [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

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
| indeks | int | Indeks DocumentInfo. |
| stream | java.io.InputStream | Stream DocumentInfo. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe DocumentInfo. |
| kata sandi | java.lang.String | DocumentInfo kata sandi. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Tambahkan dokumen ke koleksi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo instansi. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Tambahkan halaman ke koleksi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentIndex | int | Indeks DocumentInfo. |
| pageNumber | int | PageInfo nomor. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Tambahkan halaman ke koleksi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo instansi. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Tambahkan halaman ke koleksi halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages larik. |

### clear() {#clear--}
```
public final void clear()
```


Bersihkan koleksi internal.

