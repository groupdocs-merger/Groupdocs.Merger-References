---
title: "DocumentInfo"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Initialise une nouvelle instance de la classe DocumentInfogroupdocs.merger.domain.result/documentinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.merger.domain.result/documentinfo/documentinfo/
---
## DocumentInfo constructor

Initialise une nouvelle instance de la classe [`DocumentInfo`](../../documentinfo).

```csharp
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier. |
| pages | IPageInfo[] | La liste des pages à afficher. |
| taille | Int64 | La taille du fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancé lorsque *pages* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.merger.domain/filetype)
* interface [IPageInfo](../../ipageinfo)
* class [DocumentInfo](../../documentinfo)
* namespace [GroupDocs.Merger.Domain.Result](../../../groupdocs.merger.domain.result)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
