---
title: "PreviewOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αντιπροσωπεύει τις επιλογές προεπισκόπησης εγγράφου."
type: docs
weight: 630
url: /el/net/groupdocs.merger.domain.options/previewoptions/
---
## PreviewOptions class

Αντιπροσωπεύει τις επιλογές προεπισκόπησης εγγράφου.

```csharp
public class PreviewOptions : PageOptions, IPreviewOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PreviewOptions](previewoptions#constructor_4)(CreatePageStream, PreviewMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_7)(CreatePageStream, PreviewMode, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream, ReleasePageStream, PreviewMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_5)(CreatePageStream, PreviewMode, int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_3)(CreatePageStream, ReleasePageStream, PreviewMode, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_6)(CreatePageStream, PreviewMode, int, int, RangeMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream, PreviewMode, int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |
| [PreviewOptions](previewoptions#constructor_2)(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PreviewOptions`](../previewoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/previewoptions/createstream) { get; } | Αντιπρόσωπος που ορίζει τη μέθοδο για τη δημιουργία ροής προεπισκόπησης σελίδας εξόδου. |
| [Height](../../groupdocs.merger.domain.options/previewoptions/height) { get; set; } | Ύψος προεπισκόπησης. |
| [Mode](../../groupdocs.merger.domain.options/previewoptions/mode) { get; } | Λειτουργία προεπισκόπησης. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Αποκτήστε τη συλλογή αριθμών σελίδων. |
| [ReleaseStream](../../groupdocs.merger.domain.options/previewoptions/releasestream) { get; } | Αντιπρόσωπος που ορίζει μέθοδο για την απελευθέρωση της ροής προεπισκόπησης σελίδας εξόδου. |
| [Resolution](../../groupdocs.merger.domain.options/previewoptions/resolution) { get; set; } | Ανάλυση εικόνας. |
| [Width](../../groupdocs.merger.domain.options/previewoptions/width) { get; set; } | Πλάτος προεπισκόπησης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetPathByPageNumber](../../groupdocs.merger.domain.options/previewoptions/getpathbypagenumber)(int, string) | Λαμβάνει τη πλήρη διαδρομή αρχείου του προεπισκοπούμενου εγγράφου ανά αριθμό σελίδας με καθορισμένη επέκταση. |
| [Validate](../../groupdocs.merger.domain.options/previewoptions/validate)(FileType) | Επικυρώνει τις επιλογές προεπισκόπησης. |

### Παρατηρήσεις

Όταν δεν δίνονται αριθμοί σελίδων, η λειτουργία εφαρμόζεται σε κάθε σελίδα του εγγράφου.

### Δείτε επίσης

* class [PageOptions](../pageoptions)
* interface [IPreviewOptions](../ipreviewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
