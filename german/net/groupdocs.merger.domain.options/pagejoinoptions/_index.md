---
title: "PageJoinOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Bietet Optionen für das Zusammenführen von Dokumenten."
type: docs
weight: 540
url: /de/net/groupdocs.merger.domain.options/pagejoinoptions/
---
## PageJoinOptions class

Bietet Optionen für das Zusammenführen von Dokumenten.

```csharp
public class PageJoinOptions : PageOptions, IPageJoinOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PageJoinOptions](pagejoinoptions#constructor)() | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_1)(FileType) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_7)(int[]) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_4)(FileType, int[]) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_5)(int, int) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_2)(FileType, int, int) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_6)(int, int, RangeMode) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |
| [PageJoinOptions](pagejoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialisiert eine neue Instanz der [`PageJoinOptions`](../pagejoinoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Der Typ der zu verbindenden Datei. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageOptions](../pageoptions)
* interface [IPageJoinOptions](../ipagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
