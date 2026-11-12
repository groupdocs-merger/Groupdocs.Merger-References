---
title: "OrientationOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour l'orientation de la page."
type: docs
weight: 520
url: /fr/net/groupdocs.merger.domain.options/orientationoptions/
---
## OrientationOptions class

Fournit des options pour l'orientation de la page.

```csharp
public class OrientationOptions : PageOptions, IOrientationOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [OrientationOptions](orientationoptions#constructor)(OrientationMode) | Initialise une nouvelle instance de la classe [`OrientationOptions`](../orientationoptions). |
| [OrientationOptions](orientationoptions#constructor_3)(OrientationMode, int[]) | Initialise une nouvelle instance de la classe [`OrientationOptions`](../orientationoptions). |
| [OrientationOptions](orientationoptions#constructor_1)(OrientationMode, int, int) | Initialise une nouvelle instance de la classe [`OrientationOptions`](../orientationoptions). |
| [OrientationOptions](orientationoptions#constructor_2)(OrientationMode, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`OrientationOptions`](../orientationoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/orientationoptions/mode) { get; } | Obtient le mode d'orientation de la page. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |

### Remarques

Lorsque aucun numéro de page n'est fourni, l'opération s'applique à chaque page du document.

### Voir aussi

* class [PageOptions](../pageoptions)
* interface [IOrientationOptions](../iorientationoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
