---
title: "IPreviewOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Interface pour les options d'aperçu."
type: docs
weight: 320
url: /fr/net/groupdocs.merger.domain.options/ipreviewoptions/
---
## IPreviewOptions interface

Interface pour les options d'aperçu.

```csharp
public interface IPreviewOptions : IPageOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/ipreviewoptions/createstream) { get; } | Délégué qui définit la méthode pour créer le flux d'aperçu de page de sortie. |
| [Height](../../groupdocs.merger.domain.options/ipreviewoptions/height) { get; set; } | Hauteur de l'aperçu. |
| [Mode](../../groupdocs.merger.domain.options/ipreviewoptions/mode) { get; } | Obtient le mode d'aperçu. |
| [ReleaseStream](../../groupdocs.merger.domain.options/ipreviewoptions/releasestream) { get; } | Délégué qui définit la méthode pour libérer le flux d'aperçu de page de sortie. |
| [Resolution](../../groupdocs.merger.domain.options/ipreviewoptions/resolution) { get; set; } | Résolution de l'image. |
| [Width](../../groupdocs.merger.domain.options/ipreviewoptions/width) { get; set; } | Largeur de l'aperçu. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/ipreviewoptions/getpathbypagenumber)(int, string) | Obtient le chemin complet du fichier du document prévisualisé par numéro de page avec l'extension définie. |
| [Validate](../../groupdocs.merger.domain.options/ipreviewoptions/validate)(FileType) | Valide les options de fractionnement. |

### Voir aussi

* interface [IPageOptions](../ipageoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
