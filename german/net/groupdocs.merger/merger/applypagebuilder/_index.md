---
title: "ApplyPageBuilder"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Wendet Änderungen des Seiten‑Builders an."
type: docs
weight: 30
url: /de/net/groupdocs.merger/merger/applypagebuilder/
---
## Merger.ApplyPageBuilder method

Wendet Änderungen des Seiten‑Builders an.

```csharp
public void ApplyPageBuilder(PageBuilder pageBuilder)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageBuilder | PageBuilder | Der Seiten-Builder. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *pageBuilder* null ist. |
| [GroupDocsMergerException](../../../groupdocs.merger.exceptions/groupdocsmergerexception) | Wird ausgelöst, wenn die Dokumente als Bilder mit [`IImageJoinOptions`](../../../groupdocs.merger.domain.options/iimagejoinoptions) zusammengeführt werden. Laden Sie die Bilder mit einem Dokumentzieltyp, z. B. PDF oder TIFF, um deren Seiten zu erstellen. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge pages in the arbitrary order](https://docs.groupdocs.com/merger/net/merge-pages-in-arbitrary-order/)

### Siehe auch

* class [PageBuilder](../../../groupdocs.merger.domain.builders/pagebuilder)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
