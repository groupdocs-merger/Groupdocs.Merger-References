---
title: "ReleasePageStream"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Délégué qui définit la méthode pour libérer le flux d'aperçu de page de sortie."
type: docs
weight: 90
url: /fr/net/groupdocs.merger.domain.common/releasepagestream/
---
## ReleasePageStream delegate

Délégué qui définit la méthode pour libérer le flux d'aperçu de page de sortie.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream createPageStream);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de page. |
| createPageStream | Stream | Le flux créé par la méthode *createPageStream*. |

### Voir aussi

* namespace [GroupDocs.Merger.Domain.Common](../../groupdocs.merger.domain.common)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
