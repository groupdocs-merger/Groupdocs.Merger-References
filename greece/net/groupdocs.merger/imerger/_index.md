---
title: "IMerger"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Διεπαφή για την κύρια κλάση που ελέγχει τη διαδικασία συγχώνευσης εγγράφων."
type: docs
weight: 920
url: /el/net/groupdocs.merger/imerger/
---
## IMerger interface

Διεπαφή για την κύρια κλάση που ελέγχει τη διαδικασία συγχώνευσης εγγράφων.

```csharp
public interface IMerger
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPassword](../../groupdocs.merger/imerger/addpassword)(IAddPasswordOptions) | Προστατεύει το έγγραφο με κωδικό. |
| [ChangeOrientation](../../groupdocs.merger/imerger/changeorientation)(IOrientationOptions) | Εφαρμόζει νέα λειτουργία προσανατολισμού για τις καθορισμένες σελίδες. |
| [ExtractPages](../../groupdocs.merger/imerger/extractpages)(IExtractOptions) | Δημιουργεί νέο έγγραφο με ορισμένες σελίδες από το αρχικό έγγραφο. |
| [ImportDocument](../../groupdocs.merger/imerger/importdocument)(IImportDocumentOptions) | Εισάγει το έγγραφο ως συνημμένο ή ενσωματωμένο μέσω Ole. |
| [Join](../../groupdocs.merger/imerger/join#join)(Stream) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_4)(string) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_1)(Stream, IImageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_2)(Stream, IJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_3)(Stream, IPageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_5)(string, IImageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_6)(string, IJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/imerger/join#join_7)(string, IPageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [MovePage](../../groupdocs.merger/imerger/movepage)(IMoveOptions) | Μετακινεί τη σελίδα σε νέα θέση εντός εγγράφου γνωστής μορφής. |
| [RemovePages](../../groupdocs.merger/imerger/removepages)(IRemoveOptions) | Αφαιρεί σελίδες από έγγραφο γνωστής μορφής. |
| [RemovePassword](../../groupdocs.merger/imerger/removepassword)() | Αφαιρεί τον κωδικό από το έγγραφο. |
| [Rotate](../../groupdocs.merger/imerger/rotate)(IRotateOptions) | Περιστρέφει τις σελίδες του εγγράφου. |
| [Save](../../groupdocs.merger/imerger/save#save)(Stream, ISaveOptions) | Αποθηκεύει το τελικό έγγραφο στη ροή *document*. |
| [Save](../../groupdocs.merger/imerger/save#save_2)(string, ISaveOptions) | Αποθηκεύει το αρχείο του τελικού εγγράφου στο *filePath*. |
| [Save](../../groupdocs.merger/imerger/save#save_1)(string, bool, ISaveOptions) | Αποθηκεύει το αρχείο του τελικού εγγράφου στο *filePath*. |
| [Split](../../groupdocs.merger/imerger/split#split)(ISplitOptions) | Διαιρεί το μοναδικό έγγραφο σε πολλά έγγραφα. |
| [Split](../../groupdocs.merger/imerger/split#split_1)(ITextSplitOptions) | Διαιρεί το μοναδικό έγγραφο σε πολλά έγγραφα. |
| [SwapPages](../../groupdocs.merger/imerger/swappages)(ISwapOptions) | Ανταλλάσσει δύο σελίδες εντός εγγράφου γνωστής μορφής. |
| [UpdatePassword](../../groupdocs.merger/imerger/updatepassword)(IUpdatePasswordOptions) | Ενημερώνει τον υπάρχοντα κωδικό πρόσβασης για το έγγραφο. |

### Δείτε επίσης

* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
