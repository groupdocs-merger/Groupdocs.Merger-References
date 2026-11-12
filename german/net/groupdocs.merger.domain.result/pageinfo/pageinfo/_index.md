---
title: "PageInfo"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse PageInfogroupdocs.merger.domain.result/pageinfo."
type: docs
weight: 10
url: /de/net/groupdocs.merger.domain.result/pageinfo/pageinfo/
---
## PageInfo(int, bool) {#constructor}

Initialisiert eine neue Instanz der Klasse [`PageInfo`](../../pageinfo).

```csharp
public PageInfo(int number, bool visible)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitenzahl. |
| sichtbar | Boolesch | Der Seitenanzeige-Indikator. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *number* kleiner oder gleich null ist. |

### Siehe auch

* class [PageInfo](../../pageinfo)
* namespace [GroupDocs.Merger.Domain.Result](../../../groupdocs.merger.domain.result)
* assembly [GroupDocs.Merger](../../../)

---

## PageInfo(int, bool, int, int) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`PageInfo`](../../pageinfo).

```csharp
public PageInfo(int number, bool visible, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zahl | Int32 | Die Seitenzahl. |
| sichtbar | Boolesch | Der Seitenanzeige-Indikator. |
| Breite | Int32 | Die Breite der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Höhe | Int32 | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Ausgelöst, wenn *number* kleiner oder gleich null ist. |
| ArgumentException | Ausgelöst, wenn *width* kleiner oder gleich null ist. |
| ArgumentException | Ausgelöst, wenn *height* kleiner oder gleich null ist. |

### Siehe auch

* class [PageInfo](../../pageinfo)
* namespace [GroupDocs.Merger.Domain.Result](../../../groupdocs.merger.domain.result)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
