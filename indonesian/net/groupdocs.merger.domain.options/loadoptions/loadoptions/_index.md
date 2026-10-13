---
title: "LoadOptions"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Menginisialisasi instance baru dari kelas LoadOptionsgroupdocs.merger.domain.options/loadoptions."
type: docs
weight: 10
url: /id/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | FileType | Jenis file yang akan dimuat. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string password)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### Lihat Juga

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Enkoding yang digunakan saat membuka file berbasis teks seperti [`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *encoding* bernilai null. |

### Lihat Juga

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType, string password)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | FileType | Jenis file yang akan dimuat. |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | FileType | Jenis file yang akan dimuat. |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Enkoding yang digunakan saat membuka file berbasis teks seperti [`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |
| ArgumentNullException | Dilempar ketika *encoding* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| extension | String | Ekstensi file yang akan dimuat. |
| fileType | FileType | Jenis file yang akan dimuat. |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Enkoding yang digunakan saat membuka file berbasis teks seperti [`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |
| ArgumentNullException | Dilempar ketika *encoding* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| iniFileType | FileType | Jenis file yang akan diinisialisasi. |
| fileType | FileType | Jenis file yang akan dimuat. |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Enkoding yang digunakan saat membuka file berbasis teks seperti [`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau [`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *iniFileType* bernilai null. |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |
| ArgumentNullException | Dilempar ketika *encoding* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| iniFileType | FileType | Jenis file yang akan diinisialisasi. |
| fileType | FileType | Jenis file yang akan dimuat. |
| kata sandi | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *iniFileType* bernilai null. |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Menginisialisasi instance baru dari kelas [`LoadOptions`](../../loadoptions).

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| iniFileType | FileType | Jenis file yang akan diinisialisasi. |
| fileType | FileType | Jenis file yang akan dimuat. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *iniFileType* bernilai null. |
| ArgumentNullException | Dilempar ketika *fileType* bernilai null. |

### Lihat Juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
