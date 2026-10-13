---
title: "RotateOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Bietet Optionen für die Drehung von Seiten."
type: docs
weight: 670
url: /de/net/groupdocs.merger.domain.options/rotateoptions/
---
## RotateOptions class

Bietet Optionen für die Drehung von Seiten.

```csharp
public class RotateOptions : PageOptions, IRotateOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RotateOptions](rotateoptions#constructor)(RotateMode) | Initialisiert eine neue Instanz der [`RotateOptions`](../rotateoptions)-Klasse. |
| [RotateOptions](rotateoptions#constructor_3)(RotateMode, int[]) | Initialisiert eine neue Instanz der [`RotateOptions`](../rotateoptions)-Klasse. |
| [RotateOptions](rotateoptions#constructor_1)(RotateMode, int, int) | Initialisiert eine neue Instanz der [`RotateOptions`](../rotateoptions)-Klasse. |
| [RotateOptions](rotateoptions#constructor_2)(RotateMode, int, int, RangeMode) | Initialisiert eine neue Instanz der [`RotateOptions`](../rotateoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/rotateoptions/mode) { get; } | Ermittelt den Modus für die Drehung (90, 180 oder 270 Grad). |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageOptions](../pageoptions)
* interface [IRotateOptions](../irotateoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
