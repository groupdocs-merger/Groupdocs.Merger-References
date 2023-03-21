---
title: SplitOptions
second_title: GroupDocs.Merger untuk Referensi .NET API
description: Menginisialisasi instance baru dariSplitOptionsgroupdocs.merger.domain.options/splitoptions kelas.
type: docs
weight: 10
url: /id/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| pageNumbers | Int32[] | Nomor halaman. |

### Lihat juga

* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| pageNumbers | Int32[] | Nomor halaman. |
| splitMode | SplitMode | Modus pemisahan[`Mode`](../mode). |

### Lihat juga

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |

### Lihat juga

* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan sebelumnya. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |
| mode | RangeMode | Modus jangkauan. |

### Lihat juga

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| pageNumbers | Int32[] | Nomor halaman. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| pageNumbers | Int32[] | Nomor halaman. |
| splitMode | SplitMode | Modus pemisahan[`Mode`](../mode). |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |
| mode | RangeMode | Modus jangkauan. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |
| pageNumbers | Int32[] | Nomor halaman. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |
| pageNumbers | Int32[] | Nomor halaman. |
| splitMode | SplitMode | Modus pemisahan[`Mode`](../mode). |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Menginisialisasi instance baru dari[`SplitOptions`](../../splitoptions) kelas.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |
| startNumber | Int32 | Nomor halaman awal. |
| endNumber | Int32 | Nomor halaman akhir. |
| mode | RangeMode | Modus jangkauan. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../splitoptions)
* perakitan [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
