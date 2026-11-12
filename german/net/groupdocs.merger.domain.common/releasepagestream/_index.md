---
title: "ReleasePageStream"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Delegat, der eine Methode zum Freigeben des Ausgabeseiten‑Vorschau‑Streams definiert."
type: docs
weight: 90
url: /de/net/groupdocs.merger.domain.common/releasepagestream/
---
## ReleasePageStream delegate

Delegat, der eine Methode zum Freigeben des Ausgabeseiten‑Vorschau‑Streams definiert.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream createPageStream);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | Int32 | Die Seitenzahl. |
| createPageStream | Stream | Der Stream, der von der Methode *createPageStream* erstellt wurde. |

### Siehe auch

* namespace [GroupDocs.Merger.Domain.Common](../../groupdocs.merger.domain.common)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
