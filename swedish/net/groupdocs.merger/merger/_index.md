---
title: Merger
second_title: GroupDocs.Merger för .NET API-referens
description: Representerar huvudklassen som styr dokumentsammanslagningsprocessen.
type: docs
weight: 790
url: /sv/net/groupdocs.merger/merger/
---
## Merger class

Representerar huvudklassen som styr dokumentsammanslagningsprocessen.

```csharp
public class Merger : IDisposable
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_4)(Stream) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_8)(string) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initierar ny instans av[`Merger`](../merger) class. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initierar ny instans av[`Merger`](../merger) class. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Skyddar dokument med lösenord. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Tillämpar ett nytt orienteringsläge för de angivna sidorna. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Kastar resurser. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Skapar ett nytt dokument med några sidor från källdokumentet. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Genererar förhandsgranskning av dokumentsidor. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Får information om dokumentsidor: deras storlekar, maximal sidhöjd, bredden på en sida med maximal höjd. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importerar dokumentet som bilaga eller inbäddat via Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Kontrollerar om dokumentet är lösenordsskyddat. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Sammanfogar dokumenten till ett enda dokument. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Sammanfogar dokumenten till ett enda dokument. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Sammanfogar dokumenten till ett enda dokument. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Sammanfogar dokumenten till ett enda dokument. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Sammanfogar dokumenten till ett enda dokument. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Sammanfogar dokumenten till ett enda dokument. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Flyttar sidan till en ny position i dokument av känt format. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Tar bort sidor från dokument av känt format. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Tar bort lösenordet från dokumentet. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Rotera sidor i dokumentet. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Sparar resultatdokumentet i strömmen*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Sparar resultatdokumentfilen till*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Sparar resultatdokumentfilen till*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Delar upp det enskilda dokumentet till flera dokument. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Delar upp det enskilda dokumentet till flera dokument. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Byter två sidor i dokument av känt format. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Uppdaterar befintligt lösenord för dokument. |

### Se även

* namnutrymme [GroupDocs.Merger](../../groupdocs.merger)
* hopsättning [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
