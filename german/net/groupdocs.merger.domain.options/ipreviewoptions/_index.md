---
title: IPreviewOptions
second_title: GroupDocs.Merger für .NET-API-Referenz
description: Schnittstelle für die Vorschauoptionen.
type: docs
weight: 290
url: /de/net/groupdocs.merger.domain.options/ipreviewoptions/
---
## IPreviewOptions interface

Schnittstelle für die Vorschauoptionen.

```csharp
public interface IPreviewOptions : IPageOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/ipreviewoptions/createstream) { get; } | Delegierter, der die Methode zum Erstellen des Vorschaustreams der Ausgabeseite definiert. |
| [Height](../../groupdocs.merger.domain.options/ipreviewoptions/height) { get; set; } | Vorschauhöhe. |
| [Mode](../../groupdocs.merger.domain.options/ipreviewoptions/mode) { get; } | Ruft den Modus für die Vorschau ab. |
| [ReleaseStream](../../groupdocs.merger.domain.options/ipreviewoptions/releasestream) { get; } | Delegierter, der die Methode zum Freigeben des Vorschaustreams der Ausgabeseite definiert. |
| [Width](../../groupdocs.merger.domain.options/ipreviewoptions/width) { get; set; } | Vorschaubreite. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/ipreviewoptions/getpathbypagenumber)(int, string) | Ruft den vollständigen Dateipfad des in der Vorschau angezeigten Dokuments nach Seitenzahl mit definierter Erweiterung ab. |
| [Validate](../../groupdocs.merger.domain.options/ipreviewoptions/validate)(FileType) | Validiert die Teilungsoptionen. |

### Siehe auch

* interface [IPageOptions](../ipageoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* Montage [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
