---
title: Merger
second_title: .NET API Başvurusu için GroupDocs.Merger
description: Belge birleştirme sürecini kontrol eden ana sınıfı temsil eder.
type: docs
weight: 790
url: /tr/net/groupdocs.merger/merger/
---
## Merger class

Belge birleştirme sürecini kontrol eden ana sınıfı temsil eder.

```csharp
public class Merger : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_4)(Stream) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_8)(string) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Yeni örneğini başlatır[`Merger`](../merger) sınıf. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Belgeyi parola ile korur. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Belirtilen sayfalar için yeni bir yönlendirme modu uygular. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Kaynakları atar. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Kaynak belgeden bazı sayfalarla yeni bir belge oluşturur. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Belge sayfaları önizlemesi oluşturur. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Belge sayfaları hakkında bilgi alır: boyutları, maksimum sayfa yüksekliği, maksimum yüksekliğe sahip bir sayfanın genişliği. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Belgeyi ek olarak veya Ole. aracılığıyla katıştırılmış olarak içe aktarır |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Belgenin parola korumalı olup olmadığını kontrol eder. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Belgeleri tek bir belgede birleştirir. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Belgeleri tek bir belgede birleştirir. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Belgeleri tek bir belgede birleştirir. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Belgeleri tek bir belgede birleştirir. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Belgeleri tek bir belgede birleştirir. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Belgeleri tek bir belgede birleştirir. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Sayfayı, bilinen biçimdeki belge içinde yeni bir konuma taşır. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Bilinen biçimdeki belgedeki sayfaları kaldırır. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Belgeden şifreyi kaldırır. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Belgenin sayfalarını döndürün. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Sonuç belgesini akışa kaydeder*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Sonuç belge dosyasını şuraya kaydeder:*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Sonuç belge dosyasını şuraya kaydeder:*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Tek belgeyi birden çok belgeye böler. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Tek belgeyi birden çok belgeye böler. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Bilinen biçimdeki belgedeki iki sayfayı değiştirir. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Document. için mevcut parolayı günceller |

### Ayrıca bakınız

* ad alanı [GroupDocs.Merger](../../groupdocs.merger)
* toplantı [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
