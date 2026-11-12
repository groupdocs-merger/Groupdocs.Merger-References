---
title: "Pages"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Numéros de page pour les options de page."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.options/ipageoptions/pages/
---
## IPageOptions.Pages property

Numéros de page pour les options de page.

```csharp
public int[] Pages { get; }
```

### Remarques

Ce que signifie une liste vide est défini par l'opération à laquelle les options sont transmises : la plupart des opérations s'appliquent à chaque page du document, tandis que l'extraction, la suppression et la division nécessitent au moins un numéro de page et rejettent un appel sans celui-ci.

### Voir aussi

* interface [IPageOptions](../../ipageoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
