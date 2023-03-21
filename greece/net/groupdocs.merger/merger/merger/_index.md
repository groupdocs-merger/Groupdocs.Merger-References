---
title: Merger
second_title: GroupDocs.Merger for .NET API Reference
description: Αρχικοποιεί νέα παρουσία τουMergergroupdocs.merger/merger τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Stream document)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ευανάγνωστη ροή. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*document* είναι μηδενικό. |

### Δείτε επίσης

* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ευανάγνωστη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*document* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ευανάγνωστη ροή. |
| settings | MergerSettings | Οι ρυθμίσεις συγχώνευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*document* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Δείτε επίσης

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| document | Stream | Η ευανάγνωστη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | MergerSettings | Οι ρυθμίσεις συγχώνευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*document* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| settings | MergerSettings | Οι ρυθμίσεις συγχώνευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| getFileStream | Func`1 | Η μέθοδος που επιστρέφει αναγνώσιμη ροή. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | MergerSettings | Οι ρυθμίσεις συγχώνευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*getFileStream* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Δείτε επίσης

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(string filePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |

### Δείτε επίσης

* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου. |
| settings | MergerSettings | Οι ρυθμίσεις συγχώνευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Δείτε επίσης

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Αρχικοποιεί νέα παρουσία του[`Merger`](../../merger) τάξη.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | String | Η διαδρομή του αρχείου. |
| loadOptions | ILoadOptions | Οι επιλογές φόρτωσης εγγράφου. |
| settings | MergerSettings | Οι ρυθμίσεις συγχώνευσης. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*filePath* είναι μηδενικό ή κενό. |
| ArgumentNullException | Ρίχτηκε όταν*loadOptions* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*settings* είναι μηδενικό. |

### Δείτε επίσης

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* χώρος ονομάτων [GroupDocs.Merger](../../merger)
* συνέλευση [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
