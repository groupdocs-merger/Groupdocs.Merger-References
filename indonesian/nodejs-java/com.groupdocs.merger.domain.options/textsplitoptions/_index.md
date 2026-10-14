---
title: "TextSplitOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk pemisahan teks dokumen."
type: docs
weight: 39
url: /id/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Menyediakan opsi untuk pemisahan teks dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMode()](#getMode--) | Mode untuk pemisahan teks. |
| [getLineNumbers()](#getLineNumbers--) | Nomor baris untuk pemisahan teks. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Memvalidasi opsi pemisahan. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Mendapatkan jalur file lengkap dokumen yang dibagi berdasarkan indeks dengan ekstensi yang ditentukan. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory untuk membuat atau melepaskan aliran pratinjau halaman output. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lineNumbers | int[] | Nomor baris untuk pemisahan teks. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | int | Mode untuk pemisahan teks. |
| lineNumbers | int[] | Nomor baris untuk pemisahan teks. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\\{0\\}.doc' atau 'c:/split\\{0\\}.\\{1\\}' dengan ekstensi yang sudah ditentukan. |
| lineNumbers | int[] | Nomor baris untuk pemisahan teks. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | java.lang.String | Format jalur file, misalnya 'c:/split\\{0\\}.doc' atau 'c:/split\\{0\\}.\\{1\\}' dengan ekstensi yang sudah ditentukan. |
| mode | int | Mode untuk pemisahan teks. |
| lineNumbers | int[] | Nomor baris untuk pemisahan teks. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| lineNumbers | int[] | Nomor baris untuk pemisahan teks. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Menginisialisasi instance baru dari kelas [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data hasil pemisahan output. |
| mode | int | Mode untuk pemisahan teks. |
| lineNumbers | int[] | Nomor baris untuk pemisahan teks. |

### getMode() {#getMode--}
```
public final int getMode()
```


Mode untuk pemisahan teks.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Nomor baris untuk pemisahan teks.

**Returns:**
int[]
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


Mendapatkan jalur file lengkap dokumen yang dibagi berdasarkan indeks dengan ekstensi yang ditentukan.

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
