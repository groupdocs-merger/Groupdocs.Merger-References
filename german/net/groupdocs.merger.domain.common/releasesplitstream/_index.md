---
title: "ReleaseSplitStream"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Delegat, der eine Methode zum Freigeben des Ausgabesplit‑Streams definiert."
type: docs
weight: 100
url: /de/net/groupdocs.merger.domain.common/releasesplitstream/
---
## ReleaseSplitStream delegate

Delegat, der eine Methode zum Freigeben des Ausgabesplit‑Streams definiert.

```csharp
public delegate void ReleaseSplitStream(int number, Stream createSplitStream);
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seiten- oder Zeilennummer, die für das Aufteilen des Dokuments verwendet wird. |
| createSplitStream | Stream | Der Stream, der von der *createSplitStream*-Methode erstellt wird. |

### Siehe auch

* namespace [GroupDocs.Merger.Domain.Common](../../groupdocs.merger.domain.common)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
