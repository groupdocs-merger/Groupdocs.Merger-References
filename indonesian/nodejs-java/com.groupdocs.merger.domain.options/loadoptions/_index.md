---
title: "LoadOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk pemuatan dokumen."
type: docs
weight: 16
url: /id/nodejs-java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Menyediakan opsi untuk pemuatan dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Tipe file yang akan dimuat. |
| [getExtension()](#getExtension--) | Ekstensi file yang akan diinisialisasi. |
| [getPassword()](#getPassword--) | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| [getEncoding()](#getEncoding--) | Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | java.nio.charset.Charset | Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | java.nio.charset.Charset | Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | java.lang.String | Ekstensi file yang akan dimuat. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | java.nio.charset.Charset | Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan diinisialisasi. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | java.nio.charset.Charset | Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan diinisialisasi. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |
| kata sandi | java.lang.String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


Menginisialisasi instance baru dari kelas [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan diinisialisasi. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file yang akan dimuat. |

### getType() {#getType--}
```
public final FileType getType()
```


Tipe file yang akan dimuat.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ekstensi file yang akan diinisialisasi.

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Kata sandi untuk membuka file yang dilindungi kata sandi.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Encoding yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Nilai default adalah System.Text.Encoding.Default (java.nio.charset.Charset).

**Returns:**
java.nio.charset.Charset
