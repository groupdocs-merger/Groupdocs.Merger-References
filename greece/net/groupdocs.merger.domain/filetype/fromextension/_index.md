---
title: "FromExtension"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αντιστοιχίζει την επέκταση αρχείου στον τύπο αρχείου."
type: docs
weight: 740
url: /el/net/groupdocs.merger.domain/filetype/fromextension/
---
## FileType.FromExtension method

Αντιστοιχίζει την επέκταση αρχείου στον τύπο αρχείου.

```csharp
public static FileType FromExtension(string extension)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επέκταση | String | Επέκταση αρχείου (συμπεριλαμβανομένου του σημείου "."). |

### Τιμή Επιστροφής

Όταν ο τύπος αρχείου υποστηρίζεται, το επιστρέφει· διαφορετικά, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [`Unknown`](../unknown).

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Αναβαίνει όταν το *extension* είναι null ή κενή συμβολοσειρά. |

### Δείτε επίσης

* class [FileType](../../filetype)
* namespace [GroupDocs.Merger.Domain](../../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
