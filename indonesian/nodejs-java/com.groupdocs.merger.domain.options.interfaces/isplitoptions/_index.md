---
title: "ISplitOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk opsi pemisahan."
type: docs
weight: 33
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Antarmuka untuk opsi pemisahan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMode()](#getMode--) | Mendapatkan mode untuk pemisahan halaman. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Memvalidasi opsi pemisahan. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Mendapatkan jalur file lengkap dokumen yang dibagi berdasarkan indeks dengan ekstensi yang ditentukan. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegasi yang mendefinisikan metode untuk membuat aliran split output. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Mendapatkan mode untuk pemisahan halaman.

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

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegasi yang mendefinisikan metode untuk membuat aliran split output.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
