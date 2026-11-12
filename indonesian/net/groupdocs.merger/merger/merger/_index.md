---
title: "Merger"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Menginisialisasi instance baru dari kelas Mergergroupdocs.merger/merger."
type: docs
weight: 10
url: /id/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Stream document)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran yang dapat dibaca. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |

### Lihat Juga

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran yang dapat dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |
| ArgumentNullException | Dilempar ketika *loadOptions* bernilai null. |

### Lihat Juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran yang dapat dibaca. |
| settings | MergerSettings | Pengaturan Merger. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |
| ArgumentNullException | Dilempar ketika *settings* bernilai null. |

### Lihat Juga

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran yang dapat dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |
| settings | MergerSettings | Pengaturan Merger. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *document* bernilai null. |
| ArgumentNullException | Dilempar ketika *loadOptions* bernilai null. |
| ArgumentNullException | Dilempar ketika *settings* bernilai null. |

### Lihat Juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *getFileStream* bernilai null. |

### Lihat Juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *getFileStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *loadOptions* bernilai null. |

### Lihat Juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | MergerSettings | Pengaturan Merger. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *getFileStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *settings* bernilai null. |

### Lihat Juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| getFileStream | Func`1 | Metode yang mengembalikan aliran yang dapat dibaca. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |
| settings | MergerSettings | Pengaturan Merger. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *getFileStream* bernilai null. |
| ArgumentNullException | Dilempar ketika *loadOptions* bernilai null. |
| ArgumentNullException | Dilempar ketika *settings* bernilai null. |

### Lihat Juga

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(string filePath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |

### Lihat Juga

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |
| ArgumentNullException | Dilempar ketika *loadOptions* bernilai null. |

### Lihat Juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file. |
| settings | MergerSettings | Pengaturan Merger. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |
| ArgumentNullException | Dilempar ketika *settings* bernilai null. |

### Lihat Juga

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Menginisialisasi instance baru dari kelas [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file. |
| loadOptions | ILoadOptions | Opsi pemuatan dokumen. |
| settings | MergerSettings | Pengaturan Merger. |

### Pengecualian

| eksepsi | kondisi |
| --- | --- |
| ArgumentNullException | Dilempar ketika *filePath* bernilai null atau kosong. |
| ArgumentNullException | Dilempar ketika *loadOptions* bernilai null. |
| ArgumentNullException | Dilempar ketika *settings* bernilai null. |

### Lihat Juga

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
