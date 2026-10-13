---
title: "Συγχωνευτής"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αρχικοποιεί νέα παρουσία της κλάσης Mergergroupdocs.merger/merger."
type: docs
weight: 10
url: /el/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |

### Δείτε επίσης

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η αναγνώσιμη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *loadOptions* είναι null. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η αναγνώσιμη ροή. |
| settings | MergerSettings | Οι ρυθμίσεις Merger. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *settings* είναι null. |

### Δείτε επίσης

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| έγγραφο | Stream | Η αναγνώσιμη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | MergerSettings | Οι ρυθμίσεις Merger. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν το *document* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *loadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *settings* είναι null. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *getFileStream* είναι null. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *getFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *loadOptions* είναι null. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | MergerSettings | Οι ρυθμίσεις Merger. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *getFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *settings* είναι null. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | MergerSettings | Οι ρυθμίσεις Merger. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *getFileStream* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *loadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *settings* είναι null. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |

### Δείτε επίσης

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *loadOptions* είναι null. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |
| settings | MergerSettings | Οι ρυθμίσεις Merger. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *settings* είναι null. |

### Δείτε επίσης

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Αρχικοποιεί νέα παρουσία της κλάσης [`Merger`](../../merger).

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή αρχείου. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | MergerSettings | Οι ρυθμίσεις Merger. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκτοπίζεται όταν *filePath* είναι null ή κενό. |
| ArgumentNullException | Εκτοπίζεται όταν *loadOptions* είναι null. |
| ArgumentNullException | Εκτοπίζεται όταν *settings* είναι null. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
