---
title: "SpreadsheetJoinOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Die Optionen für das Zusammenführen von Tabellenkalkulationen."
type: docs
weight: 720
url: /de/net/groupdocs.merger.domain.options/spreadsheetjoinoptions/
---
## SpreadsheetJoinOptions class

Die Optionen für das Zusammenführen von Tabellenkalkulationen.

```csharp
public class SpreadsheetJoinOptions : PageJoinOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor)() | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_1)(FileType) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_7)(int[]) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_4)(FileType, int[]) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_5)(int, int) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_2)(FileType, int, int) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_6)(int, int, RangeMode) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialisiert eine neue Instanz der [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/mode) { get; set; } | Der Tabellenblatt‑Zusammenführungsmodus. Der Standardwert ist Worksheets. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |
| [SheetMatching](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/sheetmatching) { get; set; } | Wie die Arbeitsblätter der zusammengeführten Tabelle mit den Ergebnis‑Arbeitsblättern gepaart werden. Der Standardwert ist ByIndex. Hat keine Auswirkung im Worksheets‑Modus. |
| [SkipRows](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/skiprows) { get; set; } | Die Anzahl der führenden Zeilen, die in jedem angehängten Arbeitsblatt der zusammengeführten Tabelle übersprungen werden, zum Beispiel eine Kopfzeile. Hat keine Auswirkung im Worksheets‑Modus. Darf nicht negativ sein. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Der Typ der zu verbindenden Datei. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
