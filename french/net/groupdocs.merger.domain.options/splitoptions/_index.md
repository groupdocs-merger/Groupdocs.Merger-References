---
title: "SplitOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour la division des pages du document."
type: docs
weight: 700
url: /fr/net/groupdocs.merger.domain.options/splitoptions/
---
## SplitOptions class

Fournit des options pour la division des pages du document.

```csharp
public class SplitOptions : PageOptions, ISplitOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SplitOptions](splitoptions#constructor)(CreateSplitStream) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_8)(CreateSplitStream, int[]) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_1)(CreateSplitStream, ReleaseSplitStream) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_12)(string, int[]) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_6)(CreateSplitStream, int, int) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_9)(CreateSplitStream, int[], SplitMode) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_4)(CreateSplitStream, ReleaseSplitStream, int[]) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_10)(string, int, int) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_13)(string, int[], SplitMode) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_7)(CreateSplitStream, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_2)(CreateSplitStream, ReleaseSplitStream, int, int) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_5)(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_11)(string, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |
| [SplitOptions](splitoptions#constructor_3)(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) | Initialise une nouvelle instance de la classe [`SplitOptions`](../splitoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/splitoptions/createstream) { get; } | Délégué qui définit la méthode pour créer le flux de division de sortie. |
| [Mode](../../groupdocs.merger.domain.options/splitoptions/mode) { get; } | Obtient le mode de fractionnement des pages. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Obtenir la collection des numéros de page. |
| [ReleaseStream](../../groupdocs.merger.domain.options/splitoptions/releasestream) { get; } | Délégué qui définit la méthode pour libérer le flux de division de sortie. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/splitoptions/getpathbyindex)(int, string) | Obtient le chemin complet du fichier du document fractionné par indice avec l'extension prédéfinie. |
| [Validate](../../groupdocs.merger.domain.options/splitoptions/validate)(FileType) | Valide les options de fractionnement. |

### Remarques

Au moins un numéro de page est requis ; un appel sans numéro de page est rejeté.

### Voir aussi

* class [PageOptions](../pageoptions)
* interface [ISplitOptions](../isplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
