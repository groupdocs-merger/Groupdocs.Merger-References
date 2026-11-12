---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Bietet Optionen zum Aufteilen von Dokumenttext."
type: docs
weight: 760
url: /de/net/groupdocs.merger.domain.options/textsplitoptions/
---
## TextSplitOptions class

Bietet Optionen zum Aufteilen von Dokumenttext.

```csharp
public class TextSplitOptions : ITextSplitOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextSplitOptions](textsplitoptions#constructor_3)(CreateSplitStream, int[]) | Initialisiert eine neue Instanz der [`TextSplitOptions`](../textsplitoptions)-Klasse. |
| [TextSplitOptions](textsplitoptions#constructor_5)(string, int[]) | Initialisiert eine neue Instanz der [`TextSplitOptions`](../textsplitoptions)-Klasse. |
| [TextSplitOptions](textsplitoptions#constructor_1)(CreateSplitStream, ReleaseSplitStream, int[]) | Initialisiert eine neue Instanz der [`TextSplitOptions`](../textsplitoptions)-Klasse. |
| [TextSplitOptions](textsplitoptions#constructor_2)(CreateSplitStream, TextSplitMode, int[]) | Initialisiert eine neue Instanz der [`TextSplitOptions`](../textsplitoptions)-Klasse. |
| [TextSplitOptions](textsplitoptions#constructor_4)(string, TextSplitMode, int[]) | Initialisiert eine neue Instanz der [`TextSplitOptions`](../textsplitoptions)-Klasse. |
| [TextSplitOptions](textsplitoptions#constructor)(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) | Initialisiert eine neue Instanz der [`TextSplitOptions`](../textsplitoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/textsplitoptions/createstream) { get; } | Delegat, der eine Methode definiert, um einen Ausgabesplit‑Stream zu erstellen. |
| [LineNumbers](../../groupdocs.merger.domain.options/textsplitoptions/linenumbers) { get; } | Zeilennummern für die Textaufteilung. |
| [Mode](../../groupdocs.merger.domain.options/textsplitoptions/mode) { get; } | Modus für die Textaufteilung. |
| [ReleaseStream](../../groupdocs.merger.domain.options/textsplitoptions/releasestream) { get; } | Delegat, der eine Methode zum Freigeben des Ausgabesplit‑Streams definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/textsplitoptions/getpathbyindex)(int, string) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments anhand des Index mit definierter Erweiterung. |
| [Validate](../../groupdocs.merger.domain.options/textsplitoptions/validate)(FileType) | Validiert die Aufteilungsoptionen. |

### Siehe auch

* interface [ITextSplitOptions](../itextsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
