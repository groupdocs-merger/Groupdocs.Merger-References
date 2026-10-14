---
title: "RotateOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk rotasi halaman."
type: docs
weight: 33
url: /id/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Menyediakan opsi untuk rotasi halaman.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMode()](#getMode--) | Mendapatkan mode untuk memutar (90, 180, atau 270 derajat). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateMode | int | Mode rotasi dari Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateMode | int | Mode rotasi dari Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Nomor halaman. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateMode | int | Mode rotasi dari Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Menginisialisasi instance baru dari kelas [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rotateMode | int | Mode rotasi dari Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### getMode() {#getMode--}
```
public final int getMode()
```


Mendapatkan mode untuk memutar (90, 180, atau 270 derajat).

**Returns:**
int
