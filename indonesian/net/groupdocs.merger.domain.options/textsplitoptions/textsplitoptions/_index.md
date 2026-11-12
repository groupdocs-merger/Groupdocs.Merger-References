---
title: "TextSplitOptions"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Menginisialisasi instance baru dari kelas TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions."
type: docs
weight: 10
url: /id/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Menginisialisasi instance baru dari kelas [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format path file, misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat Juga

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Menginisialisasi instance baru dari kelas [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePathFormat | String | Format path file, misalnya 'c:/split{0}.doc' atau 'c:/split{0}.{1}' dengan ekstensi yang sudah ditentukan. |
| mode | TextSplitMode | Mode untuk pemisahan teks. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat Juga

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Menginisialisasi instance baru dari kelas [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Menginisialisasi instance baru dari kelas [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| mode | TextSplitMode | Mode untuk pemisahan teks. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Menginisialisasi instance baru dari kelas [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Menginisialisasi instance baru dari kelas [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metode yang menginstansiasi stream yang digunakan untuk menulis data hasil split output. |
| releaseSplitStream | ReleaseSplitStream | Metode yang melepaskan stream yang dibuat oleh metode createPageStream. |
| mode | TextSplitMode | Mode untuk pemisahan teks. |
| lineNumbers | Int32[] | Nomor baris untuk pemisahan teks. |

### Lihat Juga

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
