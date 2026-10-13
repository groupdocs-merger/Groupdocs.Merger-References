---
title: "Συγχωνευτής"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία συγχώνευσης εγγράφων."
type: docs
weight: 960
url: /el/net/groupdocs.merger/merger/
---
## Merger class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία συγχώνευσης εγγράφων.

```csharp
public class Merger : IDisposable, IMerger
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_4)(Stream) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_8)(string) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_11)(string, MergerSettings) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Αρχικοποιεί νέο αντικείμενο της κλάσης [`Merger`](../merger). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Προστατεύει το έγγραφο με κωδικό. |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | Εφαρμόζει αλλαγές του δημιουργού σελίδων. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Εφαρμόζει νέα λειτουργία προσανατολισμού για τις καθορισμένες σελίδες. |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | Δημιουργεί νέο δημιουργό σελίδων με προκαθορισμένη συλλογή εγγράφων. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Αποδεσμεύει πόρους. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Δημιουργεί νέο έγγραφο με ορισμένες σελίδες από το αρχικό έγγραφο. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Δημιουργεί προεπισκόπηση σελίδων εγγράφου. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Λαμβάνει πληροφορίες για τις σελίδες του εγγράφου: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Εισάγει το έγγραφο ως συνημμένο ή ενσωματωμένο μέσω Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Ελέγχει αν το έγγραφο είναι προστατευμένο με κωδικό. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Μετακινεί τη σελίδα σε νέα θέση εντός εγγράφου γνωστής μορφής. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Αφαιρεί σελίδες από έγγραφο γνωστής μορφής. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Αφαιρεί τον κωδικό από το έγγραφο. |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | Περιστρέφει εικόνα ή σελίδες του εγγράφου. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream, ISaveOptions) | Αποθηκεύει το τελικό έγγραφο στη ροή *document*. |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, ISaveOptions) | Αποθηκεύει το αρχείο του τελικού εγγράφου στο *filePath*. |
| [Save](../../groupdocs.merger/merger/save#save_1)(string, bool, ISaveOptions) | Αποθηκεύει το αρχείο του τελικού εγγράφου στο *filePath*. |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Διαιρεί το μοναδικό έγγραφο σε πολλά έγγραφα. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Διαιρεί το μοναδικό έγγραφο σε πολλά έγγραφα. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Ανταλλάσσει δύο σελίδες εντός εγγράφου γνωστής μορφής. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Ενημερώνει τον υπάρχοντα κωδικό πρόσβασης για το έγγραφο. |

### Δείτε επίσης

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
