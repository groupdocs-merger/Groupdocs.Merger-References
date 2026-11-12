---
title: "SplitOptions"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Menginisialisasi instance baru dari kelas SplitOptionsgroupdocs.merger.domain.options/splitoptions."
type: docs
weight: 10
url: /id/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| pageNumbers | Int32[] | Nomor halaman. |

### Lihat Juga

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| pageNumbers | Int32[] | Nomor halaman. |
| splitMode | SplitMode | Mode pemisahan dari [`Mode`](../mode). |

### Lihat Juga

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |

### Lihat Juga

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format jalur file, misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |
| mode | RangeMode | Mode rentang. |

### Lihat Juga

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| pageNumbers | Int32[] | Nomor halaman. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| pageNumbers | Int32[] | Nomor halaman. |
| splitMode | SplitMode | Mode pemisahan dari [`Mode`](../mode). |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |
| mode | RangeMode | Mode rentang. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |
| pageNumbers | Int32[] | Nomor halaman. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |
| pageNumbers | Int32[] | Nomor halaman. |
| splitMode | SplitMode | Mode pemisahan dari [`Mode`](../mode). |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Menginisialisasi instance baru dari kelas [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |
| mode | RangeMode | Mode rentang. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
