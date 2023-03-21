---
title: Merger
second_title: GroupDocs.Merger untuk Referensi .NET API
description: Menginisialisasi instance baruMergergroupdocs.merger/merger kelas.
type: docs
weight: 10
url: /id/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Stream document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran yang bisa dibaca. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*document* adalah nol. |

### Lihat juga

* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran yang bisa dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*document* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |

### Lihat juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran yang bisa dibaca. |
| settings | MergerSettings | Pengaturan Penggabungan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*document* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Lihat juga

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran yang bisa dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |
| settings | MergerSettings | Pengaturan Penggabungan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*document* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Lihat juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |

### Lihat juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |

### Lihat juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | MergerSettings | Pengaturan Penggabungan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Lihat juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |
| settings | MergerSettings | Pengaturan Penggabungan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*getFileStream* adalah nol. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Lihat juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*filePath* adalah null atau kosong. |

### Lihat juga

* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*filePath* adalah null atau kosong. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |

### Lihat juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file. |
| settings | MergerSettings | Pengaturan Penggabungan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*filePath* adalah null atau kosong. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Lihat juga

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Menginisialisasi instance baru[`Merger`](../../merger) kelas.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |
| settings | MergerSettings | Pengaturan Penggabungan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar kapan*filePath* adalah null atau kosong. |
| ArgumentNullException | Dilempar kapan*loadOptions* adalah nol. |
| ArgumentNullException | Dilempar kapan*settings* adalah nol. |

### Lihat juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ruang nama [GroupDocs.Merger](../../merger)
* perakitan [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
