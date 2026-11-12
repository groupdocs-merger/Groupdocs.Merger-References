---
title: "FromExtension"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Ordnet Dateierweiterungen Dateitypen zu."
type: docs
weight: 740
url: /de/net/groupdocs.merger.domain/filetype/fromextension/
---
## FileType.FromExtension method

Ordnet Dateierweiterungen Dateitypen zu.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Erweiterung | String | Dateierweiterung (einschließlich des Punktes "."). |

### Rückgabewert

Wenn der Dateityp unterstützt wird, wird er zurückgegeben, andernfalls wird der Standard‑[`Unknown`](../unknown)-Dateityp zurückgegeben.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *extension* null oder ein leerer String ist. |

### Siehe auch

* class [FileType](../../filetype)
* namespace [GroupDocs.Merger.Domain](../../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
