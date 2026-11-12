---
title: "ISplitOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Interface pour les options de division de page."
type: docs
weight: 370
url: /fr/net/groupdocs.merger.domain.options/isplitoptions/
---
## ISplitOptions interface

Interface pour les options de division de page.

```csharp
public interface ISplitOptions : IPageOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/isplitoptions/createstream) { get; } | Délégué qui définit la méthode pour créer le flux de division de sortie. |
| [Mode](../../groupdocs.merger.domain.options/isplitoptions/mode) { get; } | Obtient le mode de fractionnement des pages. |
| [ReleaseStream](../../groupdocs.merger.domain.options/isplitoptions/releasestream) { get; } | Délégué qui définit la méthode pour libérer le flux de division de sortie. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/isplitoptions/getpathbyindex)(int, string) | Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie. |
| [Validate](../../groupdocs.merger.domain.options/isplitoptions/validate)(FileType) | Valide les options de fractionnement. |

### Voir aussi

* interface [IPageOptions](../ipageoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
