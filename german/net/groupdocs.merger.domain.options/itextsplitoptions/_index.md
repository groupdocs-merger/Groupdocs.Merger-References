---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Schnittstelle für die Textteilungsoptionen."
type: docs
weight: 390
url: /de/net/groupdocs.merger.domain.options/itextsplitoptions/
---
## ITextSplitOptions interface

Schnittstelle für die Textteilungsoptionen.

```csharp
public interface ITextSplitOptions : IOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/itextsplitoptions/createstream) { get; } | Delegat, der eine Methode definiert, um einen Ausgabesplit‑Stream zu erstellen. |
| [LineNumbers](../../groupdocs.merger.domain.options/itextsplitoptions/linenumbers) { get; } | Zeilennummern für die Textaufteilung. |
| [Mode](../../groupdocs.merger.domain.options/itextsplitoptions/mode) { get; } | Modus für die Textaufteilung. |
| [ReleaseStream](../../groupdocs.merger.domain.options/itextsplitoptions/releasestream) { get; } | Delegat, der eine Methode zum Freigeben des Ausgabesplit‑Streams definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/itextsplitoptions/getpathbyindex)(int, string) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments anhand des Index mit definierter Erweiterung. |
| [Validate](../../groupdocs.merger.domain.options/itextsplitoptions/validate)(FileType) | Validiert die Aufteilungsoptionen. |

### Siehe auch

* interface [IOptions](../ioptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
