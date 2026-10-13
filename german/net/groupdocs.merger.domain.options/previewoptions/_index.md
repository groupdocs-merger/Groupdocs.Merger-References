---
title: "PreviewOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Stellt Optionen für die Dokumentvorschau dar."
type: docs
weight: 630
url: /de/net/groupdocs.merger.domain.options/previewoptions/
---
## PreviewOptions class

Stellt Optionen für die Dokumentvorschau dar.

```csharp
public class PreviewOptions : PageOptions, IPreviewOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PreviewOptions](previewoptions#constructor_4)(CreatePageStream, PreviewMode) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor_7)(CreatePageStream, PreviewMode, int[]) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream, ReleasePageStream, PreviewMode) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor_5)(CreatePageStream, PreviewMode, int, int) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor_3)(CreatePageStream, ReleasePageStream, PreviewMode, int[]) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor_6)(CreatePageStream, PreviewMode, int, int, RangeMode) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream, PreviewMode, int, int) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |
| [PreviewOptions](previewoptions#constructor_2)(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) | Initialisiert eine neue Instanz der [`PreviewOptions`](../previewoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/previewoptions/createstream) { get; } | Delegat, der eine Methode definiert, um einen Ausgabeseiten‑Vorschau‑Stream zu erstellen. |
| [Height](../../groupdocs.merger.domain.options/previewoptions/height) { get; set; } | Vorschauhöhe. |
| [Mode](../../groupdocs.merger.domain.options/previewoptions/mode) { get; } | Modus für die Vorschau. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |
| [ReleaseStream](../../groupdocs.merger.domain.options/previewoptions/releasestream) { get; } | Delegat, der eine Methode zum Freigeben des Ausgabeseiten‑Vorschau‑Streams definiert. |
| [Resolution](../../groupdocs.merger.domain.options/previewoptions/resolution) { get; set; } | Bildauflösung. |
| [Width](../../groupdocs.merger.domain.options/previewoptions/width) { get; set; } | Vorschaubreite. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/previewoptions/getpathbypagenumber)(int, string) | Ermittelt den vollständigen Dateipfad des nach Seitenzahl vorgestellten Dokuments mit definierter Erweiterung. |
| [Validate](../../groupdocs.merger.domain.options/previewoptions/validate)(FileType) | Validiert die Vorschauoptionen. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageOptions](../pageoptions)
* interface [IPreviewOptions](../ipreviewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
