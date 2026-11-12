---
title: "SplitOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Bietet Optionen zum Aufteilen von Dokumentseiten."
type: docs
weight: 700
url: /de/net/groupdocs.merger.domain.options/splitoptions/
---
## SplitOptions class

Bietet Optionen zum Aufteilen von Dokumentseiten.

```csharp
public class SplitOptions : PageOptions, ISplitOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SplitOptions](splitoptions#constructor)(CreateSplitStream) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_8)(CreateSplitStream, int[]) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_1)(CreateSplitStream, ReleaseSplitStream) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_12)(string, int[]) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_6)(CreateSplitStream, int, int) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_9)(CreateSplitStream, int[], SplitMode) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_4)(CreateSplitStream, ReleaseSplitStream, int[]) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_10)(string, int, int) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_13)(string, int[], SplitMode) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_7)(CreateSplitStream, int, int, RangeMode) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_2)(CreateSplitStream, ReleaseSplitStream, int, int) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_5)(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_11)(string, int, int, RangeMode) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |
| [SplitOptions](splitoptions#constructor_3)(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) | Initialisiert eine neue Instanz der [`SplitOptions`](../splitoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/splitoptions/createstream) { get; } | Delegat, der eine Methode definiert, um einen Ausgabesplit‑Stream zu erstellen. |
| [Mode](../../groupdocs.merger.domain.options/splitoptions/mode) { get; } | Ermittelt den Modus für die Seitenteilung. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |
| [ReleaseStream](../../groupdocs.merger.domain.options/splitoptions/releasestream) { get; } | Delegat, der eine Methode zum Freigeben des Ausgabesplit‑Streams definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/splitoptions/getpathbyindex)(int, string) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments nach Index mit vordefinierter Erweiterung. |
| [Validate](../../groupdocs.merger.domain.options/splitoptions/validate)(FileType) | Validiert die Aufteilungsoptionen. |

### Bemerkungen

Mindestens eine Seitenzahl ist erforderlich; ein Aufruf ohne Seitenzahlen wird abgelehnt.

### Siehe auch

* class [PageOptions](../pageoptions)
* interface [ISplitOptions](../isplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
