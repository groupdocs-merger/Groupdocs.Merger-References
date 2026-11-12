---
title: "OrientationOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Bietet Optionen für die Seitenausrichtung."
type: docs
weight: 520
url: /de/net/groupdocs.merger.domain.options/orientationoptions/
---
## OrientationOptions class

Bietet Optionen für die Seitenausrichtung.

```csharp
public class OrientationOptions : PageOptions, IOrientationOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OrientationOptions](orientationoptions#constructor)(OrientationMode) | Initialisiert eine neue Instanz der [`OrientationOptions`](../orientationoptions)-Klasse. |
| [OrientationOptions](orientationoptions#constructor_3)(OrientationMode, int[]) | Initialisiert eine neue Instanz der [`OrientationOptions`](../orientationoptions)-Klasse. |
| [OrientationOptions](orientationoptions#constructor_1)(OrientationMode, int, int) | Initialisiert eine neue Instanz der [`OrientationOptions`](../orientationoptions)-Klasse. |
| [OrientationOptions](orientationoptions#constructor_2)(OrientationMode, int, int, RangeMode) | Initialisiert eine neue Instanz der [`OrientationOptions`](../orientationoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/orientationoptions/mode) { get; } | Ermittelt den Modus für die Seitenausrichtung. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageOptions](../pageoptions)
* interface [IOrientationOptions](../iorientationoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
