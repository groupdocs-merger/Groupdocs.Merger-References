---
title: "SpreadsheetJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Les options de fusion de la feuille de calcul."
type: docs
weight: 720
url: /fr/net/groupdocs.merger.domain.options/spreadsheetjoinoptions/
---
## SpreadsheetJoinOptions class

Les options de fusion de la feuille de calcul.

```csharp
public class SpreadsheetJoinOptions : PageJoinOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor)() | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_1)(FileType) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_7)(int[]) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_4)(FileType, int[]) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_5)(int, int) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_2)(FileType, int, int) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_6)(int, int, RangeMode) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/mode) { get; set; } | Le mode de jointure de la feuille de calcul. La valeur par défaut est Worksheets. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |
| [SheetMatching](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/sheetmatching) { get; set; } | Comment les feuilles de calcul du classeur joint sont associées aux feuilles de calcul résultantes. La valeur par défaut est ByIndex. N'a aucun effet en mode Worksheets. |
| [SkipRows](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/skiprows) { get; set; } | Le nombre de lignes initiales ignorées dans chaque feuille de calcul ajoutée du classeur joint, par exemple une ligne d'en-tête. N'a aucun effet en mode Worksheets. Ne doit pas être négatif. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Le type du fichier à joindre. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
