---
title: PreviewOptions
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Belge önizleme seçeneklerini temsil eder.
type: docs
weight: 530
url: /tr/net/groupdocs.merger.domain.options/previewoptions/
---
## PreviewOptions class

Belge önizleme seçeneklerini temsil eder.

```csharp
public class PreviewOptions : PageOptions, IPreviewOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PreviewOptions](previewoptions#constructor_4)(CreatePageStream, PreviewMode) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor_7)(CreatePageStream, PreviewMode, int[]) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream, ReleasePageStream, PreviewMode) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor_5)(CreatePageStream, PreviewMode, int, int) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor_3)(CreatePageStream, ReleasePageStream, PreviewMode, int[]) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor_6)(CreatePageStream, PreviewMode, int, int, RangeMode) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream, PreviewMode, int, int) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |
| [PreviewOptions](previewoptions#constructor_2)(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) | Yeni bir örneğini başlatır.[`PreviewOptions`](../previewoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/previewoptions/createstream) { get; } | Çıktı sayfası önizleme akışı oluşturmak için yöntemi tanımlayan temsilci. |
| [Height](../../groupdocs.merger.domain.options/previewoptions/height) { get; set; } | Önizleme yüksekliği. |
| [Mode](../../groupdocs.merger.domain.options/previewoptions/mode) { get; } | Önizleme modu. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Sayfa numaraları koleksiyonunu alın. |
| [ReleaseStream](../../groupdocs.merger.domain.options/previewoptions/releasestream) { get; } | Çıktı sayfası önizleme akışını yayınlama yöntemini tanımlayan temsilci. |
| [Width](../../groupdocs.merger.domain.options/previewoptions/width) { get; set; } | Önizleme genişliği. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/previewoptions/getpathbypagenumber)(int, string) | Önizlenen belgenin tam dosya yolunu tanımlı uzantıya sahip sayfa numarasına göre alır. |
| [Validate](../../groupdocs.merger.domain.options/previewoptions/validate)(FileType) | Önizleme seçeneklerini doğrular. |

### Ayrıca bakınız

* class [PageOptions](../pageoptions)
* interface [IPreviewOptions](../ipreviewoptions)
* ad alanı [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* toplantı [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->