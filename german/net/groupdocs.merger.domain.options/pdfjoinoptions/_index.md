---
title: "PdfJoinOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Die PDF‑Zusammenführungsoptionen."
type: docs
weight: 580
url: /de/net/groupdocs.merger.domain.options/pdfjoinoptions/
---
## PdfJoinOptions class

Die PDF‑Zusammenführungsoptionen.

```csharp
public class PdfJoinOptions : PageJoinOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfJoinOptions](pdfjoinoptions#constructor)() | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_1)(FileType) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_7)(int[]) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_4)(FileType, int[]) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_5)(int, int) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_2)(FileType, int, int) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_6)(int, int, RangeMode) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |
| [PdfJoinOptions](pdfjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Initialisiert eine neue Instanz der [`PdfJoinOptions`](../pdfjoinoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Erhalte die Sammlung von Seitenzahlen. |
| [PreserveAccessibility](../../groupdocs.merger.domain.options/pdfjoinoptions/preserveaccessibility) { get; set; } | Gibt an, ob die PDF-Barrierefreiheit (getaggte PDF-Struktur) beim Zusammenführen erhalten bleiben soll. Wenn true, enthält das zusammengeführte Dokument automatisch generierte Barrierefreiheits‑Tags für die PDF/UA-Konformität. Standard ist false. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Der Typ der zu verbindenden Datei. |
| [UseBookmarks](../../groupdocs.merger.domain.options/pdfjoinoptions/usebookmarks) { get; set; } | Gibt an, ob alle Lesezeichen standardmäßig kopiert werden. |

### Bemerkungen

Wenn keine Seitenzahlen angegeben sind, wird die Operation auf jede Seite des Dokuments angewendet.

### Siehe auch

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
