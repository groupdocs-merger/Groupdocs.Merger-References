---
title: "ISplitOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Schnittstelle für die Seitenteilungsoptionen."
type: docs
weight: 370
url: /de/net/groupdocs.merger.domain.options/isplitoptions/
---
## ISplitOptions interface

Schnittstelle für die Seitenteilungsoptionen.

```csharp
public interface ISplitOptions : IPageOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/isplitoptions/createstream) { get; } | Delegat, der eine Methode definiert, um einen Ausgabesplit‑Stream zu erstellen. |
| [Mode](../../groupdocs.merger.domain.options/isplitoptions/mode) { get; } | Ermittelt den Modus für die Seitenteilung. |
| [ReleaseStream](../../groupdocs.merger.domain.options/isplitoptions/releasestream) { get; } | Delegat, der eine Methode zum Freigeben des Ausgabesplit‑Streams definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/isplitoptions/getpathbyindex)(int, string) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments anhand des Index mit definierter Erweiterung. |
| [Validate](../../groupdocs.merger.domain.options/isplitoptions/validate)(FileType) | Validiert die Aufteilungsoptionen. |

### Siehe auch

* interface [IPageOptions](../ipageoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
