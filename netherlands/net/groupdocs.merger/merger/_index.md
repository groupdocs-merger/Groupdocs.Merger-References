---
title: Merger
second_title: GroupDocs.Merger voor .NET API-referentie
description: Vertegenwoordigt de hoofdklasse die het proces voor het samenvoegen van documenten bestuurt.
type: docs
weight: 790
url: /nl/net/groupdocs.merger/merger/
---
## Merger class

Vertegenwoordigt de hoofdklasse die het proces voor het samenvoegen van documenten bestuurt.

```csharp
public class Merger : IDisposable
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_4)(Stream) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_8)(string) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initialiseert nieuw exemplaar van[`Merger`](../merger) klasse. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Beschermt document met wachtwoord. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Past een nieuwe oriëntatiemodus toe op de opgegeven pagina's. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Verwijdert bronnen. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Maakt een nieuw document met enkele pagina's uit het brondocument. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Genereert voorbeeld van documentpagina's. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Krijgt informatie over documentpagina's: hun afmetingen, maximale paginahoogte, de breedte van een pagina met de maximale hoogte. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importeert het document als bijlage of ingebed via Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Controleert of het document met een wachtwoord is beveiligd. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Voegt de documenten samen tot één enkel document. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Voegt de documenten samen tot één enkel document. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Voegt de documenten samen tot één enkel document. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Voegt de documenten samen tot één enkel document. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Voegt de documenten samen tot één enkel document. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Voegt de documenten samen tot één enkel document. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Verplaatst de pagina naar een nieuwe positie binnen een document met een bekend formaat. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Verwijdert pagina's uit een document met een bekend formaat. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Verwijdert wachtwoord uit document. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Roteer pagina's van het document. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Slaat het resultaatdocument op in de stream*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Slaat het resultaatdocumentbestand op in*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Slaat het resultaatdocumentbestand op in*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Splitst het enkele document op in meerdere documenten. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Splitst het enkele document op in meerdere documenten. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Verwisselt twee pagina's binnen een document met een bekend formaat. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Werkt bestaand wachtwoord bij voor document. |

### Zie ook

* naamruimte [GroupDocs.Merger](../../groupdocs.merger)
* montage [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
