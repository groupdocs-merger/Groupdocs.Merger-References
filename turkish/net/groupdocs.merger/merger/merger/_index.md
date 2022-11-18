---
title: Merger
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Yeni örneğini başlatırMergergroupdocs.merger/merger sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Stream document)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Okunabilir akış. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*document* boş. |

### Ayrıca bakınız

* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Okunabilir akış. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*document* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |

### Ayrıca bakınız

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Okunabilir akış. |
| settings | MergerSettings | Birleştirme ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*document* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Ayrıca bakınız

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Okunabilir akış. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. |
| settings | MergerSettings | Birleştirme ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*document* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Ayrıca bakınız

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |

### Ayrıca bakınız

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |

### Ayrıca bakınız

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |
| settings | MergerSettings | Birleştirme ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Ayrıca bakınız

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| getFileStream | Func`1 | Okunabilir akış döndüren yöntem. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. |
| settings | MergerSettings | Birleştirme ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*getFileStream* boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Ayrıca bakınız

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*filePath* null veya boş. |

### Ayrıca bakınız

* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |

### Ayrıca bakınız

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| settings | MergerSettings | Birleştirme ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Ayrıca bakınız

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Yeni örneğini başlatır[`Merger`](../../merger) sınıf.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Dosya yolu. |
| loadOptions | ILoadOptions | Belge yükleme seçenekleri. |
| settings | MergerSettings | Birleştirme ayarları. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Ne zaman atıldı*filePath* null veya boş. |
| ArgumentNullException | Ne zaman atıldı*loadOptions* boş. |
| ArgumentNullException | Ne zaman atıldı*settings* boş. |

### Ayrıca bakınız

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* ad alanı [GroupDocs.Merger](../../merger)
* toplantı [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
