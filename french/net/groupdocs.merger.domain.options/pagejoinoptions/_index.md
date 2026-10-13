---
title: "PageJoinOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour la fusion de documents."
type: docs
weight: 540
url: /fr/net/groupdocs.merger.domain.options/pagejoinoptions/
---
## PageJoinOptions class

Fournit des options pour la fusion de documents.

```csharp
public class PageJoinOptions : PageOptions, IPageJoinOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PageJoinOptions](pagejoinoptions#constructor)() | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_1)(FileType) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_7)(int[]) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_4)(FileType, int[]) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_5)(int, int) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_2)(FileType, int, int) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_6)(int, int, RangeMode) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |
| [PageJoinOptions](pagejoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`PageJoinOptions`](../pagejoinoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Le type du fichier à joindre. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageOptions](../pageoptions)
* interface [IPageJoinOptions](../ipagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
