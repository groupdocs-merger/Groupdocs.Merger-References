---
title: PreviewOptions
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Yeni bir örneğini başlatır.PreviewOptionsgroupdocs.merger.domain.options/previewoptions sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |
| pageNumbers | Int32[] | Sayfa numaraları. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |
| mode | RangeMode | Menzil modu. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releasePageStream | ReleasePageStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releasePageStream | ReleasePageStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |
| pageNumbers | Int32[] | Sayfa numaraları. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releasePageStream | ReleasePageStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Yeni bir örneğini başlatır.[`PreviewOptions`](../../previewoptions) sınıf.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createPageStream | CreatePageStream | Çıkış sayfası verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releasePageStream | ReleasePageStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| previewMode | PreviewMode | önizleme modu[`Mode`](../mode) |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |
| mode | RangeMode | Menzil modu. |

### Ayrıca bakınız

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../previewoptions)
* toplantı [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
