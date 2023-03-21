---
title: LoadOptions
second_title: GroupDocs.Merger untuk Referensi .NET API
description: Menginisialisasi instance baruLoadOptionsgroupdocs.merger.domain.options/loadoptions kelas.
type: docs
weight: 10
url: /id/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(FileType fileType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fileType | FileType | Jenis file yang akan dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(string password)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### Lihat juga

* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Pengkodean yang digunakan saat membuka file berbasis teks seperti[`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*encoding* adalah nol. |

### Lihat juga

* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(FileType fileType, string password)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fileType | FileType | Jenis file yang akan dimuat. |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fileType | FileType | Jenis file yang akan dimuat. |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Pengkodean yang digunakan saat membuka file berbasis teks seperti[`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |
| ArgumentNullException | Dilempar kapan*encoding* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| extension | String | Ekstensi file yang akan dimuat. |
| fileType | FileType | Jenis file yang akan dimuat. |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Pengkodean yang digunakan saat membuka file berbasis teks seperti[`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |
| ArgumentNullException | Dilempar kapan*encoding* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| iniFileType | FileType | Jenis file untuk init. |
| fileType | FileType | Jenis file yang akan dimuat. |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| encoding | Encoding | Pengkodean yang digunakan saat membuka file berbasis teks seperti[`CSV`](../../../groupdocs.merger.domain/filetype/csv) atau[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*iniFileType* adalah nol. |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |
| ArgumentNullException | Dilempar kapan*encoding* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| iniFileType | FileType | Jenis file untuk init. |
| fileType | FileType | Jenis file yang akan dimuat. |
| password | String | Kata sandi untuk membuka file yang dilindungi kata sandi. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*iniFileType* adalah nol. |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Menginisialisasi instance baru[`LoadOptions`](../../loadoptions) kelas.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| iniFileType | FileType | Jenis file untuk init. |
| fileType | FileType | Jenis file yang akan dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*iniFileType* adalah nol. |
| ArgumentNullException | Dilempar kapan*fileType* adalah nol. |

### Lihat juga

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../loadoptions)
* perakitan [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
