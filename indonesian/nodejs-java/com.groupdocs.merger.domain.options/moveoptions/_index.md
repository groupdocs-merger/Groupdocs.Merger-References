---
title: "MoveOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk memindahkan halaman dokumen."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Menyediakan opsi untuk memindahkan halaman dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Menginisialisasi instance baru dari kelas [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Mendapatkan atau mengatur nomor halaman yang akan dipindahkan. |
| [getNewPageNumber()](#getNewPageNumber--) | Mendapatkan atau mengatur nomor halaman baru. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Menginisialisasi instance baru dari kelas [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumberToMove | int | Nomor halaman yang akan dipindahkan. |
| newPageNumber | int | Nomor halaman baru. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Mendapatkan atau mengatur nomor halaman yang akan dipindahkan.

Nilai: Nomor halaman yang akan dipindahkan.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Mendapatkan atau mengatur nomor halaman baru.

Nilai: Nomor halaman baru.

**Returns:**
int
