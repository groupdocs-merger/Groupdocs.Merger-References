---
title: "PreviewOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Représente les options d'aperçu du document."
type: docs
weight: 630
url: /fr/net/groupdocs.merger.domain.options/previewoptions/
---
## PreviewOptions class

Représente les options d'aperçu du document.

```csharp
public class PreviewOptions : PageOptions, IPreviewOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PreviewOptions](previewoptions#constructor_4)(CreatePageStream, PreviewMode) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_7)(CreatePageStream, PreviewMode, int[]) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream, ReleasePageStream, PreviewMode) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_5)(CreatePageStream, PreviewMode, int, int) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_3)(CreatePageStream, ReleasePageStream, PreviewMode, int[]) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_6)(CreatePageStream, PreviewMode, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream, PreviewMode, int, int) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_2)(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/previewoptions/createstream) { get; } | Délégué qui définit la méthode pour créer le flux d'aperçu de page de sortie. |
| [Height](../../groupdocs.merger.domain.options/previewoptions/height) { get; set; } | Hauteur de l'aperçu. |
| [Mode](../../groupdocs.merger.domain.options/previewoptions/mode) { get; } | Mode d'aperçu. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |
| [ReleaseStream](../../groupdocs.merger.domain.options/previewoptions/releasestream) { get; } | Délégué qui définit la méthode pour libérer le flux d'aperçu de page de sortie. |
| [Resolution](../../groupdocs.merger.domain.options/previewoptions/resolution) { get; set; } | Résolution de l'image. |
| [Width](../../groupdocs.merger.domain.options/previewoptions/width) { get; set; } | Largeur de l'aperçu. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/previewoptions/getpathbypagenumber)(int, string) | Obtient le chemin complet du fichier du document prévisualisé par numéro de page avec l'extension définie. |
| [Validate](../../groupdocs.merger.domain.options/previewoptions/validate)(FileType) | Valide les options d'aperçu. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageOptions](../pageoptions)
* interface [IPreviewOptions](../ipreviewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
