---
title: "DocumentInfo"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Mendefinisikan properti deskripsi dokumen."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Mendefinisikan properti deskripsi dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Menginisialisasi instance baru dari kelas [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Menginisialisasi instance baru dari kelas [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Menginisialisasi instance baru dari kelas [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getIndex()](#getIndex--) | Indeks dokumen. |
| [getStream()](#getStream--) | Aliran dokumen. |
| [getPassword()](#getPassword--) | Kata sandi dokumen. |
| [getType()](#getType--) | Mendapatkan tipe file. |
| [getPages()](#getPages--) | Mendefinisikan koleksi halaman dokumen. |
| [getPageCount()](#getPageCount--) | Jumlah halaman dokumen. |
| [getSize()](#getSize--) | Ukuran dokumen dalam byte |
| [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Menginisialisasi instance baru dari kelas [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Jenis berkas. |
| kata sandi | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Menginisialisasi instance baru dari kelas [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Jenis berkas. |
| kata sandi | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Daftar halaman untuk dilihat. |
| ukuran | long | Ukuran file. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Menginisialisasi instance baru dari kelas [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Jenis berkas. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Daftar halaman untuk dilihat. |
| ukuran | long | Ukuran file. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Indeks dokumen.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Aliran dokumen.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi dokumen.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Mendapatkan tipe file.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Mendefinisikan koleksi halaman dokumen.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Jumlah halaman dokumen.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Ukuran dokumen dalam byte

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan objek saat ini.
