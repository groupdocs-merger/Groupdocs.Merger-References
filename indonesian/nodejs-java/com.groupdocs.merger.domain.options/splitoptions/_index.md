---
title: "SplitOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk pemisahan halaman dokumen."
type: docs
weight: 36
url: /id/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Menyediakan opsi untuk pemisahan halaman dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMode()](#getMode--) | Mendapatkan mode untuk pemisahan halaman. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Memvalidasi opsi pemisahan. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Mendapatkan jalur lengkap file dokumen yang dipisahkan berdasarkan indeks dengan ekstensi yang telah ditentukan. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory untuk membuat atau melepaskan aliran pratinjau halaman output. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumbers | int[] | Nomor halaman. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\{0\}.doc' atau 'c:/split\{0\}.\{1\}' dengan ekstensi yang sudah ditentukan. |
| pageNumbers | int[] | Nomor halaman. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\{0\}.doc' atau 'c:/split\{0\}.\{1\}' dengan ekstensi yang sudah ditentukan. |
| pageNumbers | int[] | Nomor halaman. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\{0\}.doc' atau 'c:/split\{0\}.\{1\}' dengan ekstensi yang sudah ditentukan. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\{0\}.doc' atau 'c:/split\{0\}.\{1\}' dengan ekstensi yang sudah ditentukan. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\{0\}.doc' atau 'c:/split\{0\}.\{1\}' dengan ekstensi yang sudah ditentukan. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | java.lang.Integer | Mode rentang. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\{0\}.doc' atau 'c:/split\{0\}.\{1\}' dengan ekstensi yang sudah ditentukan. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| pageNumbers | int[] | Nomor halaman. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| pageNumbers | int[] | Nomor halaman. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | java.lang.Integer | Mode rentang. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Menginisialisasi sebuah instance baru dari kelas [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| splitMode | int | Mode pemisahan dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### getMode() {#getMode--}
```
public final int getMode()
```


Mendapatkan mode untuk pemisahan halaman.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Memvalidasi opsi pemisahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file dari kelas [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Mendapatkan jalur lengkap file dokumen yang dipisahkan berdasarkan indeks dengan ekstensi yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks | int | Indeks dokumen yang dipisah. |
| ekstensi | java.lang.String | Ekstensi file. |

**Returns:**
java.lang.String - Jalur file lengkap.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory untuk membuat atau melepaskan aliran pratinjau halaman output.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
