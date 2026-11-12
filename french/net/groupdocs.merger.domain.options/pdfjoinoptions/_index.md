---
title: "PdfJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Les options de fusion PDF."
type: docs
weight: 580
url: /fr/net/groupdocs.merger.domain.options/pdfjoinoptions/
---
## PdfJoinOptions class

Les options de fusion PDF.

```csharp
public class PdfJoinOptions : PageJoinOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfJoinOptions](pdfjoinoptions#constructor)() | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_1)(FileType) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_7)(int[]) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_4)(FileType, int[]) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_5)(int, int) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_2)(FileType, int, int) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_6)(int, int, RangeMode) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`PdfJoinOptions`](../pdfjoinoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |
| [PreserveAccessibility](../../groupdocs.merger.domain.options/pdfjoinoptions/preserveaccessibility) { get; set; } | Indique si l'accessibilité PDF (structure PDF balisée) doit être préservée lors de la fusion. Lorsque vrai, le document fusionné aura des balises d'accessibilité générées automatiquement pour la conformité PDF/UA. La valeur par défaut est false. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Le type du fichier à joindre. |
| [UseBookmarks](../../groupdocs.merger.domain.options/pdfjoinoptions/usebookmarks) { get; set; } | Indique si tous les signets seront copiés par défaut. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
