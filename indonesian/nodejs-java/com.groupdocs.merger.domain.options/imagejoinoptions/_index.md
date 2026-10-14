---
title: "ImageJoinOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Opsi penggabungan gambar."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Opsi penggabungan gambar.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Tipe berkas gambar. |
| [getMode()](#getMode--) | Mode penggabungan gambar. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe berkas gambar. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageJoinMode | int | Mode penggabungan gambar. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Menginisialisasi instance baru dari kelas [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe berkas gambar. |
| imageJoinMode | int | Mode penggabungan gambar. |

### getType() {#getType--}
```
public final FileType getType()
```


Tipe berkas gambar.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


Mode penggabungan gambar.

**Returns:**
int
