---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Διεπαφή για τις επιλογές προεπισκόπησης."
type: docs
weight: 320
url: /el/net/groupdocs.merger.domain.options/ipreviewoptions/
---
## IPreviewOptions interface

Διεπαφή για τις επιλογές προεπισκόπησης.

```csharp
public interface IPreviewOptions : IPageOptions
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/ipreviewoptions/createstream) { get; } | Αντιπρόσωπος που ορίζει τη μέθοδο για τη δημιουργία ροής προεπισκόπησης σελίδας εξόδου. |
| [Height](../../groupdocs.merger.domain.options/ipreviewoptions/height) { get; set; } | Ύψος προεπισκόπησης. |
| [Mode](../../groupdocs.merger.domain.options/ipreviewoptions/mode) { get; } | Λαμβάνει τη λειτουργία προεπισκόπησης. |
| [ReleaseStream](../../groupdocs.merger.domain.options/ipreviewoptions/releasestream) { get; } | Αντιπρόσωπος που ορίζει μέθοδο για την απελευθέρωση της ροής προεπισκόπησης σελίδας εξόδου. |
| [Resolution](../../groupdocs.merger.domain.options/ipreviewoptions/resolution) { get; set; } | Ανάλυση εικόνας. |
| [Width](../../groupdocs.merger.domain.options/ipreviewoptions/width) { get; set; } | Πλάτος προεπισκόπησης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/ipreviewoptions/getpathbypagenumber)(int, string) | Λαμβάνει τη πλήρη διαδρομή αρχείου του προεπισκοπούμενου εγγράφου ανά αριθμό σελίδας με καθορισμένη επέκταση. |
| [Validate](../../groupdocs.merger.domain.options/ipreviewoptions/validate)(FileType) | Επικυρώνει τις επιλογές διαχωρισμού. |

### Δείτε επίσης

* interface [IPageOptions](../ipageoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
