---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Παρέχει επιλογές για το διαχωρισμό κειμένου εγγράφου."
type: docs
weight: 760
url: /el/net/groupdocs.merger.domain.options/textsplitoptions/
---
## TextSplitOptions class

Παρέχει επιλογές για το διαχωρισμό κειμένου εγγράφου.

```csharp
public class TextSplitOptions : ITextSplitOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TextSplitOptions](textsplitoptions#constructor_3)(CreateSplitStream, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_5)(string, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_1)(CreateSplitStream, ReleaseSplitStream, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_2)(CreateSplitStream, TextSplitMode, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor_4)(string, TextSplitMode, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSplitOptions`](../textsplitoptions). |
| [TextSplitOptions](textsplitoptions#constructor)(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [`TextSplitOptions`](../textsplitoptions). |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/textsplitoptions/createstream) { get; } | Αντιπρόσωπος που ορίζει τη μέθοδο για τη δημιουργία ροής διαχωρισμού εξόδου. |
| [LineNumbers](../../groupdocs.merger.domain.options/textsplitoptions/linenumbers) { get; } | Αριθμοί γραμμής για διαχωρισμό κειμένου. |
| [Mode](../../groupdocs.merger.domain.options/textsplitoptions/mode) { get; } | Λειτουργία για διαχωρισμό κειμένου. |
| [ReleaseStream](../../groupdocs.merger.domain.options/textsplitoptions/releasestream) { get; } | Αντιπρόσωπος που ορίζει μέθοδο για την απελευθέρωση της ροής διαίρεσης εξόδου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/textsplitoptions/getpathbyindex)(int, string) | Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου με βάση το δείκτη και την καθορισμένη επέκταση. |
| [Validate](../../groupdocs.merger.domain.options/textsplitoptions/validate)(FileType) | Επικυρώνει τις επιλογές διαχωρισμού. |

### Δείτε επίσης

* interface [ITextSplitOptions](../itextsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
