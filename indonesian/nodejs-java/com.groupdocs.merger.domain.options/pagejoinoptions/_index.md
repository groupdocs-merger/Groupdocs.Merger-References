---
title: "PageJoinOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk penggabungan dokumen."
type: docs
weight: 25
url: /id/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Menyediakan opsi untuk penggabungan dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Tipe file yang akan digabungkan. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumbers | int[] | Nomor halaman. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |
| pageNumbers | int[] | Nomor halaman. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### getType() {#getType--}
```
public final FileType getType()
```


Tipe file yang akan digabungkan.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
