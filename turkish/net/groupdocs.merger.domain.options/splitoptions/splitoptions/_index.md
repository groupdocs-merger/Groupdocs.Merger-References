---
title: SplitOptions
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Yeni bir örneğini başlatır.SplitOptionsgroupdocs.merger.domain.options/splitoptions sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Önceden tanımlanmış uzantıya sahip dosya yolu biçimi, örneğin 'c:/split{0}.doc' veya 'c:/split{0}.{1}'. |
| pageNumbers | Int32[] | Sayfa numaraları. |

### Ayrıca bakınız

* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Önceden tanımlanmış uzantıya sahip dosya yolu biçimi, örneğin 'c:/split{0}.doc' veya 'c:/split{0}.{1}'. |
| pageNumbers | Int32[] | Sayfa numaraları. |
| splitMode | SplitMode | bölme modu[`Mode`](../mode). |

### Ayrıca bakınız

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Önceden tanımlanmış uzantıya sahip dosya yolu biçimi, örneğin 'c:/split{0}.doc' veya 'c:/split{0}.{1}'. |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |

### Ayrıca bakınız

* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Önceden tanımlanmış uzantıya sahip dosya yolu biçimi, örneğin 'c:/split{0}.doc' veya 'c:/split{0}.{1}'. |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |
| mode | RangeMode | Menzil modu. |

### Ayrıca bakınız

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| pageNumbers | Int32[] | Sayfa numaraları. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| pageNumbers | Int32[] | Sayfa numaraları. |
| splitMode | SplitMode | bölme modu[`Mode`](../mode). |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |
| mode | RangeMode | Menzil modu. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| pageNumbers | Int32[] | Sayfa numaraları. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| pageNumbers | Int32[] | Sayfa numaraları. |
| splitMode | SplitMode | bölme modu[`Mode`](../mode). |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Yeni bir örneğini başlatır.[`SplitOptions`](../../splitoptions) sınıf.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| startNumber | Int32 | Başlangıç sayfası numarası. |
| endNumber | Int32 | Son sayfa numarası. |
| mode | RangeMode | Menzil modu. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../splitoptions)
* toplantı [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
