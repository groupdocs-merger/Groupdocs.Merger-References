---
title: TextSplitOptions
second_title: GroupDocs.Merger untuk Referensi .NET API
description: Menginisialisasi instance baru dariTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions kelas.
type: docs
weight: 10
url: /id/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Menginisialisasi instance baru dari[`TextSplitOptions`](../../textsplitoptions) kelas.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat juga

* class [TextSplitOptions](../../textsplitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Menginisialisasi instance baru dari[`TextSplitOptions`](../../textsplitoptions) kelas.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePathFormat | String | Format jalur file misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan. |
| mode | TextSplitMode | Mode untuk pemisahan teks. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat juga

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Menginisialisasi instance baru dari[`TextSplitOptions`](../../textsplitoptions) kelas.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Menginisialisasi instance baru dari[`TextSplitOptions`](../../textsplitoptions) kelas.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| mode | TextSplitMode | Mode untuk pemisahan teks. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Menginisialisasi instance baru dari[`TextSplitOptions`](../../textsplitoptions) kelas.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* perakitan [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Menginisialisasi instance baru dari[`TextSplitOptions`](../../textsplitoptions) kelas.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginisiasi aliran yang digunakan untuk menulis data pemisahan keluaran. |
| releaseSplitStream | ReleaseSplitStream | Metode yang merilis aliran yang dibuat dengan metode createPageStream. |
| mode | TextSplitMode | Mode untuk pemisahan teks. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* ruang nama [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* perakitan [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
