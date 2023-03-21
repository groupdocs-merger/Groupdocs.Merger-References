---
title: Merger
second_title: GroupDocs.Merger for .NET API Reference
description: Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία συγχώνευσης εγγράφων.
type: docs
weight: 790
url: /el/net/groupdocs.merger/merger/
---
## Merger class

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία συγχώνευσης εγγράφων.

```csharp
public class Merger : IDisposable
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_4)(Stream) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_8)(string) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Αρχικοποιεί νέα παρουσία του[`Merger`](../merger) τάξη. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Προστατεύει το έγγραφο με κωδικό πρόσβασης. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Εφαρμόζει μια νέα λειτουργία προσανατολισμού για τις καθορισμένες σελίδες. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Διαθέτει πόρους. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Δημιουργεί ένα νέο έγγραφο με μερικές σελίδες από το έγγραφο προέλευσης. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Δημιουργεί προεπισκόπηση σελίδων εγγράφου. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Λαμβάνει πληροφορίες σχετικά με τις σελίδες εγγράφων: τα μεγέθη τους, το μέγιστο ύψος σελίδας, το πλάτος μιας σελίδας με το μέγιστο ύψος. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Εισάγει το έγγραφο ως συνημμένο ή ενσωματωμένο μέσω Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Ελέγχει εάν το έγγραφο προστατεύεται με κωδικό πρόσβασης. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Ενώνει τα έγγραφα σε ένα μόνο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Ενώνει τα έγγραφα σε ένα μόνο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Ενώνει τα έγγραφα σε ένα μόνο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Ενώνει τα έγγραφα σε ένα μόνο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Ενώνει τα έγγραφα σε ένα μόνο έγγραφο. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Ενώνει τα έγγραφα σε ένα μόνο έγγραφο. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Μετακινεί τη σελίδα σε μια νέα θέση εντός εγγράφου γνωστής μορφής. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Αφαιρεί σελίδες από έγγραφο γνωστής μορφής. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Αφαιρεί τον κωδικό πρόσβασης από το έγγραφο. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Περιστροφή σελίδων του εγγράφου. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Αποθηκεύει το έγγραφο αποτελεσμάτων στη ροή*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Αποθηκεύει το αρχείο του εγγράφου αποτελέσματος*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Αποθηκεύει το αρχείο του εγγράφου αποτελέσματος*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Διαχωρίζει το μεμονωμένο έγγραφο στα πολλαπλά έγγραφα. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Διαχωρίζει το μεμονωμένο έγγραφο στα πολλαπλά έγγραφα. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Εναλλάσσει δύο σελίδες σε έγγραφο γνωστής μορφής. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Ενημερώνει τον υπάρχοντα κωδικό πρόσβασης για το έγγραφο. |

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Merger](../../groupdocs.merger)
* συνέλευση [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
