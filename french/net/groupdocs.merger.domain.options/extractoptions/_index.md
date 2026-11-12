---
title: "ExtractOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour extraire les pages du document."
type: docs
weight: 130
url: /fr/net/groupdocs.merger.domain.options/extractoptions/
---
## ExtractOptions class

Fournit des options pour extraire les pages du document.

```csharp
public class ExtractOptions : PageOptions, IExtractOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ExtractOptions](extractoptions#constructor)() | Initialise une nouvelle instance de la classe [`ExtractOptions`](../extractoptions). |
| [ExtractOptions](extractoptions#constructor_3)(int[]) | Initialise une nouvelle instance de la classe [`ExtractOptions`](../extractoptions). |
| [ExtractOptions](extractoptions#constructor_1)(int, int) | Initialise une nouvelle instance de la classe [`ExtractOptions`](../extractoptions). |
| [ExtractOptions](extractoptions#constructor_2)(int, int, RangeMode) | Initialise une nouvelle instance de la classe [`ExtractOptions`](../extractoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |

### Remarques

Au moins un numéro de page est requis ; un appel sans numéro de page est rejeté.

### Voir aussi

* class [PageOptions](../pageoptions)
* interface [IExtractOptions](../iextractoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
