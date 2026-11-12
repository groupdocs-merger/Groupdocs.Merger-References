---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Schnittstelle für die Vorschaueinstellungen."
type: docs
weight: 320
url: /de/net/groupdocs.merger.domain.options/ipreviewoptions/
---
## IPreviewOptions interface

Schnittstelle für die Vorschaueinstellungen.

```csharp
public interface IPreviewOptions : IPageOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/ipreviewoptions/createstream) { get; } | Delegat, der eine Methode definiert, um einen Ausgabeseiten‑Vorschau‑Stream zu erstellen. |
| [Height](../../groupdocs.merger.domain.options/ipreviewoptions/height) { get; set; } | Vorschauhöhe. |
| [Mode](../../groupdocs.merger.domain.options/ipreviewoptions/mode) { get; } | Gibt den Modus für die Vorschau zurück. |
| [ReleaseStream](../../groupdocs.merger.domain.options/ipreviewoptions/releasestream) { get; } | Delegat, der eine Methode zum Freigeben des Ausgabeseiten‑Vorschau‑Streams definiert. |
| [Resolution](../../groupdocs.merger.domain.options/ipreviewoptions/resolution) { get; set; } | Bildauflösung. |
| [Width](../../groupdocs.merger.domain.options/ipreviewoptions/width) { get; set; } | Vorschaubreite. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/ipreviewoptions/getpathbypagenumber)(int, string) | Ermittelt den vollständigen Dateipfad des nach Seitenzahl vorgestellten Dokuments mit definierter Erweiterung. |
| [Validate](../../groupdocs.merger.domain.options/ipreviewoptions/validate)(FileType) | Validiert die Aufteilungsoptionen. |

### Siehe auch

* interface [IPageOptions](../ipageoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
