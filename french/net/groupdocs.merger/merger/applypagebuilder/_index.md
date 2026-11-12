---
title: "ApplyPageBuilder"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Applique les modifications du constructeur de pages."
type: docs
weight: 30
url: /fr/net/groupdocs.merger/merger/applypagebuilder/
---
## Merger.ApplyPageBuilder method

Applique les modifications du constructeur de pages.

```csharp
public void ApplyPageBuilder(PageBuilder pageBuilder)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageBuilder | PageBuilder | Le constructeur de page. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque *pageBuilder* est nul. |
| [GroupDocsMergerException](../../../groupdocs.merger.exceptions/groupdocsmergerexception) | Lancé lorsque les documents sont joints en tant qu'images avec [`IImageJoinOptions`](../../../groupdocs.merger.domain.options/iimagejoinoptions). Chargez les images avec un type de cible de document, tel que PDF ou TIFF, pour construire leurs pages. |

### Remarques

**Learn more**

* More about document merge scenarios and use cases: [How to merge pages in the arbitrary order](https://docs.groupdocs.com/merger/net/merge-pages-in-arbitrary-order/)

### Voir aussi

* class [PageBuilder](../../../groupdocs.merger.domain.builders/pagebuilder)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
