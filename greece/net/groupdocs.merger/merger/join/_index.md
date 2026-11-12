---
title: "Join"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο."
type: docs
weight: 120
url: /el/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Συνδεδεμένο έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Συνδεδεμένο έγγραφο. |
| joinOptions | IJoinOptions | Οι επιλογές σύνδεσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *joinOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Συνδεδεμένο έγγραφο. |
| joinOptions | IPageJoinOptions | Οι επιλογές σύνδεσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *joinOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Συνδεδεμένο έγγραφο. |
| joinOptions | IImageJoinOptions | Οι επιλογές σύνδεσης εικόνας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *joinOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Διαδρομή αρχείου του ενωμένου εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Διαδρομή αρχείου του ενωμένου εγγράφου. |
| joinOptions | IJoinOptions | Οι επιλογές σύνδεσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *joinOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Διαδρομή αρχείου του ενωμένου εγγράφου. |
| joinOptions | IPageJoinOptions | Οι επιλογές σύνδεσης. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *joinOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

Συνενώνει τα έγγραφα σε ένα ενιαίο έγγραφο.

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Διαδρομή αρχείου του ενωμένου εγγράφου. |
| joinOptions | IImageJoinOptions | Οι επιλογές σύνδεσης εικόνας. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *joinOptions* είναι null. |

### Παρατηρήσεις

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Δείτε επίσης

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
