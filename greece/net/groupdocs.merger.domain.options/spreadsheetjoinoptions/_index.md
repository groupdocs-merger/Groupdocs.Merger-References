---
title: "SpreadsheetJoinOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Οι επιλογές συγχώνευσης λογιστικού φύλλου."
type: docs
weight: 720
url: /el/net/groupdocs.merger.domain.options/spreadsheetjoinoptions/
---
## SpreadsheetJoinOptions class

Οι επιλογές συγχώνευσης λογιστικού φύλλου.

```csharp
public class SpreadsheetJoinOptions : PageJoinOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_1)(FileType) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_7)(int[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_4)(FileType, int[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_5)(int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_2)(FileType, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_6)(int, int, RangeMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |
| [SpreadsheetJoinOptions](spreadsheetjoinoptions#constructor_3)(FileType, int, int, RangeMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SpreadsheetJoinOptions`](../spreadsheetjoinoptions) class. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Mode](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/mode) { get; set; } | Η λειτουργία σύνδεσης λογιστικού φύλλου. Η προεπιλογή είναι Worksheets. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Αποκτήστε τη συλλογή αριθμών σελίδων. |
| [SheetMatching](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/sheetmatching) { get; set; } | Πώς τα φύλλα εργασίας του συνδεδεμένου λογιστικού φύλλου αντιστοιχίζονται με τα φύλλα εργασίας του αποτελέσματος. Η προεπιλογή είναι ByIndex. Δεν έχει καμία επίδραση στη λειτουργία Worksheets. |
| [SkipRows](../../groupdocs.merger.domain.options/spreadsheetjoinoptions/skiprows) { get; set; } | Ο αριθμός των αρχικών γραμμών που παραλείπονται σε κάθε προσαρτημένο φύλλο εργασίας του συνδεδεμένου λογιστικού φύλλου, για παράδειγμα μια γραμμή κεφαλίδας. Δεν έχει καμία επίδραση στη λειτουργία Worksheets. Δεν πρέπει να είναι αρνητικός. |
| [Type](../../groupdocs.merger.domain.options/pagejoinoptions/type) { get; } | Ο τύπος του αρχείου προς συγχώνευση. |

### Παρατηρήσεις

Όταν δεν δίνονται αριθμοί σελίδων, η λειτουργία εφαρμόζεται σε κάθε σελίδα του εγγράφου.

### Δείτε επίσης

* class [PageJoinOptions](../pagejoinoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
