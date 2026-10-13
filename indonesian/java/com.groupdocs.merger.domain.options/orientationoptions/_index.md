---
title: "OrientationOptions"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Menyediakan opsi untuk orientasi halaman."
type: docs
weight: 23
url: /id/java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Menyediakan opsi untuk orientasi halaman.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMode()](#getMode--) | Mendapatkan mode untuk orientasi halaman. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientationMode | int | Mode orientasi dari [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientationMode | int | Mode orientasi dari [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | Nomor halaman. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientationMode | int | Mode orientasi dari [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orientationMode | int | Mode orientasi dari [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### getMode() {#getMode--}
```
public final int getMode()
```


Mendapatkan mode untuk orientasi halaman.

**Returns:**
int
