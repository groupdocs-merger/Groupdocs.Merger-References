---
title: "WordJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Les options de fusion Word."
type: docs
weight: 800
url: /fr/net/groupdocs.merger.domain.options/wordjoinoptions/
---
## WordJoinOptions class

Les options de fusion Word.

```csharp
public class WordJoinOptions : PageJoinOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordJoinOptions](wordjoinoptions#constructor)() | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_1)(FileType) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_7)(int[]) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_4)(FileType, int[]) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_5)(int, int) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_2)(FileType, int, int) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_6)(int, int, RangeMode) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |
| [WordJoinOptions](wordjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`WordJoinOptions`](../wordjoinoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Compliance](../../groupdocs.merger.domain.options/wordjoinoptions/compliance) { get; set; } | Mode de conformité pour le format Word Ooxml |
| [Mode](../../groupdocs.merger.domain.options/wordjoinoptions/mode) { get; set; } | Le mode de jointure Word. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Le type du fichier à joindre. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
