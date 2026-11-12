---
title: "SplitOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Παρέχει επιλογές για το διαχωρισμό σελίδων εγγράφου."
type: docs
weight: 700
url: /el/net/groupdocs.merger.domain.options/splitoptions/
---
## SplitOptions class

Παρέχει επιλογές για το διαχωρισμό σελίδων εγγράφου.

```csharp
public class SplitOptions : PageOptions, ISplitOptions
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SplitOptions](splitoptions#constructor)(CreateSplitStream) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_8)(CreateSplitStream, int[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_1)(CreateSplitStream, ReleaseSplitStream) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_12)(string, int[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_6)(CreateSplitStream, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_9)(CreateSplitStream, int[], SplitMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_4)(CreateSplitStream, ReleaseSplitStream, int[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_10)(string, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_13)(string, int[], SplitMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_7)(CreateSplitStream, int, int, RangeMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_2)(CreateSplitStream, ReleaseSplitStream, int, int) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_5)(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_11)(string, int, int, RangeMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |
| [SplitOptions](splitoptions#constructor_3)(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) | Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../splitoptions) class. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/splitoptions/createstream) { get; } | Αντιπρόσωπος που ορίζει τη μέθοδο για τη δημιουργία ροής διαχωρισμού εξόδου. |
| [Mode](../../groupdocs.merger.domain.options/splitoptions/mode) { get; } | Λαμβάνει τη λειτουργία για διαχωρισμό σελίδων. |
| [Pages](../../groupdocs.merger.domain.options/pageoptions/pages) { get; } | Αποκτήστε τη συλλογή αριθμών σελίδων. |
| [ReleaseStream](../../groupdocs.merger.domain.options/splitoptions/releasestream) { get; } | Αντιπρόσωπος που ορίζει μέθοδο για την απελευθέρωση της ροής διαίρεσης εξόδου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/splitoptions/getpathbyindex)(int, string) | Λαμβάνει τη πλήρη διαδρομή αρχείου του διαχωρισμένου εγγράφου κατά δείκτη με προ-ορισμένη επέκταση. |
| [Validate](../../groupdocs.merger.domain.options/splitoptions/validate)(FileType) | Επικυρώνει τις επιλογές διαχωρισμού. |

### Παρατηρήσεις

Απαιτείται τουλάχιστον ένας αριθμός σελίδας· μια κλήση χωρίς αριθμούς σελίδας απορρίπτεται.

### Δείτε επίσης

* class [PageOptions](../pageoptions)
* interface [ISplitOptions](../isplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
