---
title: "ITextSplitOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Interface pour les options de division de texte."
type: docs
weight: 390
url: /fr/net/groupdocs.merger.domain.options/itextsplitoptions/
---
## ITextSplitOptions interface

Interface pour les options de division de texte.

```csharp
public interface ITextSplitOptions : IOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/itextsplitoptions/createstream) { get; } | Délégué qui définit la méthode pour créer le flux de division de sortie. |
| [LineNumbers](../../groupdocs.merger.domain.options/itextsplitoptions/linenumbers) { get; } | Numéros de ligne pour le fractionnement du texte. |
| [Mode](../../groupdocs.merger.domain.options/itextsplitoptions/mode) { get; } | Mode de fractionnement du texte. |
| [ReleaseStream](../../groupdocs.merger.domain.options/itextsplitoptions/releasestream) { get; } | Délégué qui définit la méthode pour libérer le flux de division de sortie. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/itextsplitoptions/getpathbyindex)(int, string) | Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie. |
| [Validate](../../groupdocs.merger.domain.options/itextsplitoptions/validate)(FileType) | Valide les options de fractionnement. |

### Voir aussi

* interface [IOptions](../ioptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
