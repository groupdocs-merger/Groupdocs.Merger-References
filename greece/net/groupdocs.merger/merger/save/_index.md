---
title: "Save"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αποθηκεύει το τελικό έγγραφο στη ροή εγγράφου."
type: docs
weight: 170
url: /el/net/groupdocs.merger/merger/save/
---
## Save(Stream, ISaveOptions) {#save}

Αποθηκεύει το τελικό έγγραφο στη ροή *document*.

```csharp
public IMerger Save(Stream document, ISaveOptions saveOptions = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η ροή εγγράφου. |
| saveOptions | ISaveOptions | Οι επιλογές αποθήκευσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Save(string, ISaveOptions) {#save_2}

Αποθηκεύει το αρχείο του τελικού εγγράφου στο *filePath*.

```csharp
public IMerger Save(string filePath, ISaveOptions saveOptions = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Το όνομα αρχείου ή η πλήρης διαδρομή αρχείου. |
| saveOptions | ISaveOptions | Οι επιλογές αποθήκευσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Save(string, bool, ISaveOptions) {#save_1}

Αποθηκεύει το αρχείο του τελικού εγγράφου στο *filePath*.

```csharp
public IMerger Save(string filePath, bool useDefaultDirectory, ISaveOptions saveOptions = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή ή το όνομα αρχείου σε περίπτωση χρήσης προεπιλεγμένου καταλόγου. |
| useDefaultDirectory | Boolean | Χρησιμοποιήστε τον προεπιλεγμένο κατάλογο από τις ρυθμίσεις. |
| saveOptions | ISaveOptions | Οι επιλογές αποθήκευσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [ISaveOptions](../../../groupdocs.merger.domain.options/isaveoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
