---
title: TextSplitOptions
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Yeni bir örneğini başlatır.TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Yeni bir örneğini başlatır.[`TextSplitOptions`](../../textsplitoptions) sınıf.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi, örneğin 'c:/split{0}.doc' veya 'c:/split{0}.{1}' gibi önceden tanımlanmış uzantı. |
| lineNumbers | Int32[] | Metin bölme için satır numaraları. |

### Ayrıca bakınız

* class [TextSplitOptions](../../textsplitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Yeni bir örneğini başlatır.[`TextSplitOptions`](../../textsplitoptions) sınıf.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePathFormat | String | Dosya yolu biçimi, örneğin 'c:/split{0}.doc' veya 'c:/split{0}.{1}' gibi önceden tanımlanmış uzantı. |
| mode | TextSplitMode | Metin bölme modu. |
| lineNumbers | Int32[] | Metin bölme için satır numaraları. |

### Ayrıca bakınız

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Yeni bir örneğini başlatır.[`TextSplitOptions`](../../textsplitoptions) sınıf.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| lineNumbers | Int32[] | Metin bölme için satır numaraları. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Yeni bir örneğini başlatır.[`TextSplitOptions`](../../textsplitoptions) sınıf.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| mode | TextSplitMode | Metin bölme modu. |
| lineNumbers | Int32[] | Metin bölme için satır numaraları. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Yeni bir örneğini başlatır.[`TextSplitOptions`](../../textsplitoptions) sınıf.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| lineNumbers | Int32[] | Metin bölme için satır numaraları. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* toplantı [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Yeni bir örneğini başlatır.[`TextSplitOptions`](../../textsplitoptions) sınıf.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Çıkış bölünmüş verilerini yazmak için kullanılan akışı başlatan yöntem. |
| releaseSplitStream | ReleaseSplitStream | createPageStream yöntemi tarafından oluşturulan akışı serbest bırakan yöntem. |
| mode | TextSplitMode | Metin bölme modu. |
| lineNumbers | Int32[] | Metin bölme için satır numaraları. |

### Ayrıca bakınız

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* toplantı [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
