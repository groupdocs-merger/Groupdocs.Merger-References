---
title: "Join"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Menggabungkan dokumen menjadi satu dokumen tunggal."
type: docs
weight: 120
url: /id/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(Stream document)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Dokumen yang digabungkan. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Dokumen yang digabungkan. |
| joinOptions | IJoinOptions | Opsi penggabungan. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |
| ArgumentNullException | Dilempar ketika *joinOptions* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Dokumen yang digabungkan. |
| joinOptions | IPageJoinOptions | Opsi penggabungan. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |
| ArgumentNullException | Dilempar ketika *joinOptions* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Dokumen yang digabungkan. |
| joinOptions | IImageJoinOptions | Opsi penggabungan gambar. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |
| ArgumentNullException | Dilempar ketika *joinOptions* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file dari dokumen yang digabungkan. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file dari dokumen yang digabungkan. |
| joinOptions | IJoinOptions | Opsi penggabungan. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |
| ArgumentNullException | Dilempar ketika *joinOptions* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file dari dokumen yang digabungkan. |
| joinOptions | IPageJoinOptions | Opsi penggabungan. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |
| ArgumentNullException | Dilempar ketika *joinOptions* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

Menggabungkan dokumen menjadi satu dokumen tunggal.

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file dari dokumen yang digabungkan. |
| joinOptions | IImageJoinOptions | Opsi penggabungan gambar. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |
| ArgumentNullException | Dilempar ketika *joinOptions* bernilai null. |

### Catatan

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Lihat Juga

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
