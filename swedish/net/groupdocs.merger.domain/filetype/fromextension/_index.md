---
title: FromExtension
second_title: GroupDocs.Merger för .NET API-referens
description: Mappar filtillägget till filtyp.
type: docs
weight: 610
url: /sv/net/groupdocs.merger.domain/filetype/fromextension/
---
## FileType.FromExtension method

Mappar filtillägget till filtyp.

```csharp
public static FileType FromExtension(string extension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extension | String | Filtillägg (inklusive perioden "."). |

### Returvärde

När filtypen stöds returneras den, annars returneras standard[`Unknown`](../unknown) filtyp.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | Kastas när*extension* är null eller tom sträng. |

### Se även

* class [FileType](../../filetype)
* namnutrymme [GroupDocs.Merger.Domain](../../filetype)
* hopsättning [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
