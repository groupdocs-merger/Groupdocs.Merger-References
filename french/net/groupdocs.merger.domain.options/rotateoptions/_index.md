---
title: "RotateOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour la rotation des pages."
type: docs
weight: 670
url: /fr/net/groupdocs.merger.domain.options/rotateoptions/
---
## RotateOptions class

Fournit des options pour la rotation des pages.

```csharp
public class RotateOptions : PageOptions, IRotateOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RotateOptions](rotateoptions#constructor)(RotateMode) | Initialise une nouvelle instance de la classe [`RotateOptions`](../rotateoptions). |
| [RotateOptions](rotateoptions#constructor_3)(RotateMode, int[]) | Initialise une nouvelle instance de la classe [`RotateOptions`](../rotateoptions). |
| [RotateOptions](rotateoptions#constructor_1)(RotateMode, int, int) | Initialise une nouvelle instance de la classe [`RotateOptions`](../rotateoptions). |
| [RotateOptions](rotateoptions#constructor_2)(RotateMode, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`RotateOptions`](../rotateoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/rotateoptions/mode) { get; } | Obtient le mode de rotation (90, 180 ou 270 degrés). |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageOptions](../pageoptions)
* interface [IRotateOptions](../irotateoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
