---
title: "WordJoinOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Die Optionen zum Zusammenführen von Word-Dokumenten."
type: docs
weight: 800
url: /de/net/groupdocs.merger.domain.options/wordjoinoptions/
---
## WordJoinOptions class

Die Optionen zum Zusammenführen von Word-Dokumenten.

```csharp
public class WordJoinOptions : PageJoinOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [WordJoinOptions](wordjoinoptions#constructor)() | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_1)(FileType) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_7)(int[]) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_4)(FileType, int[]) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_5)(int, int) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_2)(FileType, int, int) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_6)(int, int, RangeMode) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |
| [WordJoinOptions](wordjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialisiert eine neue Instanz der [`WordJoinOptions`](../wordjoinoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Compliance](../../groupdocs.merger.domain.options/wordjoinoptions/compliance) { get; set; } | Kompatibilitätsmodus für das Word-Ooxml-Format |
| [Mode](../../groupdocs.merger.domain.options/wordjoinoptions/mode) { get; set; } | Der Word-Zusammenführungsmodus. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Der Typ der zu verbindenden Datei. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
