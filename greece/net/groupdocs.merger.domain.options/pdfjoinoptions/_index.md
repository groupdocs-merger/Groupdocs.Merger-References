---
title: "PdfJoinOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Οι επιλογές σύνδεσης PDF."
type: docs
weight: 580
url: /el/net/groupdocs.merger.domain.options/pdfjoinoptions/
---
## PdfJoinOptions class

Οι επιλογές σύνδεσης PDF.

```csharp
public class PdfJoinOptions : PageJoinOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PdfJoinOptions](pdfjoinoptions#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_1)(FileType) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_7)(int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_4)(FileType, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_5)(int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_2)(FileType, int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_6)(int, int, RangeMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |
| [PdfJoinOptions](pdfjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`PdfJoinOptions`](../pdfjoinoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Αποκτήστε τη συλλογή αριθμών σελίδων. |
| [PreserveAccessibility](../../groupdocs.merger.domain.options/pdfjoinoptions/preserveaccessibility) { get; set; } | Δείχνει αν η προσβασιμότητα PDF (δομή PDF με ετικέτες) πρέπει να διατηρηθεί κατά τη συγχώνευση. Όταν είναι true, το συγχωνευμένο έγγραφο θα έχει αυτόματα δημιουργημένες ετικέτες προσβασιμότητας για συμμόρφωση με PDF/UA. Η προεπιλογή είναι false. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Ο τύπος του αρχείου προς συγχώνευση. |
| [UseBookmarks](../../groupdocs.merger.domain.options/pdfjoinoptions/usebookmarks) { get; set; } | Δείχνει αν όλα τα σελιδοδείκτες θα αντιγραφούν εξ ορισμού. |

### Παρατηρήσεις

Όταν δεν δίνονται αριθμοί σελίδων, η λειτουργία εφαρμόζεται σε κάθε σελίδα του εγγράφου.

### Δείτε επίσης

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
