---
title: "PageInfo"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Mendefinisikan properti deskripsi halaman."
type: docs
weight: 11
url: /id/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Mendefinisikan properti deskripsi halaman.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Menginisialisasi instance baru dari kelas [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Menginisialisasi instance baru dari kelas [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDocument()](#getDocument--) | Mendapatkan informasi dokumen. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Mendapatkan informasi dokumen. |
| [getNumber()](#getNumber--) | Mendapatkan nomor halaman. |
| [getVisible()](#getVisible--) | Menunjukkan apakah halaman terlihat atau tidak. |
| [getWidth()](#getWidth--) | Mendapatkan lebar halaman dalam piksel saat dikonversi menjadi gambar. |
| [getHeight()](#getHeight--) | Mendapatkan tinggi halaman dalam piksel saat dikonversi menjadi gambar. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Menginisialisasi instance baru dari kelas [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nomor | int | Nomor halaman. |
| terlihat | boolean | Indikator visibilitas halaman. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Menginisialisasi instance baru dari kelas [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nomor | int | Nomor halaman. |
| terlihat | boolean | Indikator visibilitas halaman. |
| lebar | int | Lebar halaman dalam piksel saat dilihat sebagai JPG atau PNG. |
| tinggi | int | Tinggi halaman dalam piksel saat dilihat sebagai JPG atau PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Mendapatkan informasi dokumen.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Mendapatkan informasi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Mendapatkan nomor halaman.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Menunjukkan apakah halaman terlihat atau tidak.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Mendapatkan lebar halaman dalam piksel saat dikonversi menjadi gambar.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Mendapatkan tinggi halaman dalam piksel saat dikonversi menjadi gambar.

**Returns:**
int
