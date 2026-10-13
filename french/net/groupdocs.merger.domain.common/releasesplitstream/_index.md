---
title: "ReleaseSplitStream"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Délégué qui définit la méthode pour libérer le flux de division de sortie."
type: docs
weight: 100
url: /fr/net/groupdocs.merger.domain.common/releasesplitstream/
---
## ReleaseSplitStream delegate

Délégué qui définit la méthode pour libérer le flux de division de sortie.

```csharp
public delegate void ReleaseSplitStream(int number, Stream createSplitStream);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de page ou de ligne utilisé pour le fractionnement du document. |
| createSplitStream | Stream | Le flux créé par la méthode *createSplitStream*. |

### Voir aussi

* namespace [GroupDocs.Merger.Domain.Common](../../groupdocs.merger.domain.common)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
