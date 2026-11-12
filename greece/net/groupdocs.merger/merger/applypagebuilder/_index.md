---
title: "ApplyPageBuilder"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Εφαρμόζει αλλαγές του δημιουργού σελίδων."
type: docs
weight: 30
url: /el/net/groupdocs.merger/merger/applypagebuilder/
---
## Merger.ApplyPageBuilder method

Εφαρμόζει αλλαγές του δημιουργού σελίδων.

```csharp
public void ApplyPageBuilder(PageBuilder pageBuilder)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pageBuilder | PageBuilder | Ο δημιουργός σελίδων. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *pageBuilder* είναι null. |
| [GroupDocsMergerException](../../../groupdocs.merger.exceptions/groupdocsmergerexception) | Εκτοπίζεται όταν τα έγγραφα συνδέονται ως εικόνες με [`IImageJoinOptions`](../../../groupdocs.merger.domain.options/iimagejoinoptions). Φορτώστε τις εικόνες με τύπο στόχου εγγράφου, όπως PDF ή TIFF, για να δημιουργήσετε τις σελίδες τους. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge pages in the arbitrary order](https://docs.groupdocs.com/merger/net/merge-pages-in-arbitrary-order/)

### Δείτε επίσης

* class [PageBuilder](../../../groupdocs.merger.domain.builders/pagebuilder)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
