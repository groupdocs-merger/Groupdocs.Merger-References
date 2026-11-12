---
title: "TextSplitOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour la division du texte du document."
type: docs
weight: 760
url: /fr/net/groupdocs.merger.domain.options/textsplitoptions/
---
## TextSplitOptions class

Fournit des options pour la division du texte du document.

```csharp
public class TextSplitOptions : ITextSplitOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextSplitOptions](textsplitoptions#constructor_3)(CreateSplitStream, int[]) | Initialise une nouvelle instance de la classe [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_5)(string, int[]) | Initialise une nouvelle instance de la classe [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_1)(CreateSplitStream, ReleaseSplitStream, int[]) | Initialise une nouvelle instance de la classe [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_2)(CreateSplitStream, TextSplitMode, int[]) | Initialise une nouvelle instance de la classe [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_4)(string, TextSplitMode, int[]) | Initialise une nouvelle instance de la classe [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor)(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) | Initialise une nouvelle instance de la classe [`TextSplitOptions`](../textsplitoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/textsplitoptions/createstream) { get; } | Délégué qui définit la méthode pour créer le flux de division de sortie. |
| [LineNumbers](../../groupdocs.merger.domain.options/textsplitoptions/linenumbers) { get; } | Numéros de ligne pour le fractionnement du texte. |
| [Mode](../../groupdocs.merger.domain.options/textsplitoptions/mode) { get; } | Mode de fractionnement du texte. |
| [ReleaseStream](../../groupdocs.merger.domain.options/textsplitoptions/releasestream) { get; } | Délégué qui définit la méthode pour libérer le flux de division de sortie. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/textsplitoptions/getpathbyindex)(int, string) | Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie. |
| [Validate](../../groupdocs.merger.domain.options/textsplitoptions/validate)(FileType) | Valide les options de fractionnement. |

### Voir aussi

* interface [ITextSplitOptions](../itextsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
