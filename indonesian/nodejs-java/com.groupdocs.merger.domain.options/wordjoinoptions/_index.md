---
title: "WordJoinOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Opsi penggabungan Word."
type: docs
weight: 43
url: /id/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Opsi penggabungan Word.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMode()](#getMode--) | Mode penggabungan Word. |
| [setMode(int value)](#setMode-int-) | Mode penggabungan Word. |
| [getCompliance()](#getCompliance--) | Mode kepatuhan untuk format Word Ooxml |
| [setCompliance(int value)](#setCompliance-int-) | Mode kepatuhan untuk format Word Ooxml |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumbers | int[] | Nomor halaman. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |
| pageNumbers | int[] | Nomor halaman. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan digabungkan. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### getMode() {#getMode--}
```
public final int getMode()
```


Mode penggabungan Word.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Mode penggabungan Word.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Mode kepatuhan untuk format Word Ooxml

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Mode kepatuhan untuk format Word Ooxml

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

