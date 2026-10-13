---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Antarmuka untuk opsi pemisahan teks."
type: docs
weight: 35
url: /id/java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Antarmuka untuk opsi pemisahan teks.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Nomor baris untuk pemisahan teks. |
| [getMode()](#getMode--) | Mode untuk pemisahan teks. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Memvalidasi opsi pemisahan. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Mendapatkan jalur file lengkap dari dokumen yang dipisah berdasarkan indeks dengan ekstensi yang ditentukan. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegasi yang mendefinisikan metode untuk membuat aliran hasil pemisahan. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Nomor baris untuk pemisahan teks.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Mode untuk pemisahan teks.

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


Mendapatkan jalur file lengkap dari dokumen yang dipisah berdasarkan indeks dengan ekstensi yang ditentukan.

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


Delegasi yang mendefinisikan metode untuk membuat aliran hasil pemisahan.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
