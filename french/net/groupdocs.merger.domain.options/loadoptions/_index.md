---
title: "LoadOptions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Fournit des options pour le chargement du document."
type: docs
weight: 450
url: /fr/net/groupdocs.merger.domain.options/loadoptions/
---
## LoadOptions class

Fournit des options pour le chargement du document.

```csharp
public class LoadOptions : ILoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LoadOptions](loadoptions#constructor)(FileType) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_6)(string) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType, FileType) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_4)(FileType, string) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_8)(string, Encoding) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_2)(FileType, FileType, string) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_5)(FileType, string, Encoding) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_3)(FileType, FileType, string, Encoding) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_7)(string, FileType, string, Encoding) | Initialise une nouvelle instance de la classe [`LoadOptions`](../loadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../groupdocs.merger.domain.options/loadoptions/encoding) { get; } | L'encodage utilisé lors de l'ouverture de fichiers texte tels que [`CSV`](../../groupdocs.merger.domain/filetype/csv) ou [`TXT`](../../groupdocs.merger.domain/filetype/txt). La valeur par défaut est Default. |
| [Extension](../../groupdocs.merger.domain.options/loadoptions/extension) { get; } | L'extension du fichier à initialiser. |
| [Password](../../groupdocs.merger.domain.options/loadoptions/password) { get; } | Le mot de passe pour ouvrir le fichier protégé par mot de passe. |
| [Type](../../groupdocs.merger.domain.options/loadoptions/type) { get; } | Le type du fichier à charger. |

### Voir aussi

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
