---
title: "IPreviewOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk opsi pratinjau."
type: docs
weight: 28
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Antarmuka untuk opsi pratinjau.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Lebar pratinjau. |
| [setWidth(int value)](#setWidth-int-) | Lebar pratinjau. |
| [getHeight()](#getHeight--) | Tinggi pratinjau. |
| [setHeight(int value)](#setHeight-int-) | Tinggi pratinjau. |
| [getResolution()](#getResolution--) | Resolusi gambar. |
| [setResolution(int value)](#setResolution-int-) | Resolusi gambar. |
| [getMode()](#getMode--) | Mendapatkan mode untuk pratinjau. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Memvalidasi opsi pemisahan. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Mendapatkan jalur lengkap file dokumen yang dipratinjau berdasarkan nomor halaman dengan ekstensi yang ditentukan. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegasi yang mendefinisikan metode untuk membuat aliran pratinjau halaman output. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Lebar pratinjau.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Lebar pratinjau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Tinggi pratinjau.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Tinggi pratinjau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Resolusi gambar.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Resolusi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Mendapatkan mode untuk pratinjau.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Memvalidasi opsi pemisahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe file dari kelas [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Mendapatkan jalur lengkap file dokumen yang dipratinjau berdasarkan nomor halaman dengan ekstensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | int | Nomor halaman pratinjau. |
| ekstensi | java.lang.String | Ekstensi file. |

**Returns:**
java.lang.String - Jalur file lengkap.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Delegasi yang mendefinisikan metode untuk membuat aliran pratinjau halaman output.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
