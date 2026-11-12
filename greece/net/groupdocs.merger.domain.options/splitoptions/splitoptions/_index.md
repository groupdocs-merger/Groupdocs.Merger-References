---
title: "SplitOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης SplitOptionsgroupdocs.merger.domain.options/splitoptions."
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη προ-ορισμένη επέκταση. |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη προ-ορισμένη επέκταση. |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |
| splitMode | SplitMode | Η λειτουργία διαίρεσης του [`Mode`](../mode). |

### Δείτε επίσης

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη προ-ορισμένη επέκταση. |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |

### Δείτε επίσης

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη προ-ορισμένη επέκταση. |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |
| mode | RangeMode | Η λειτουργία εύρους. |

### Δείτε επίσης

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |
| splitMode | SplitMode | Η λειτουργία διαίρεσης του [`Mode`](../mode). |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |
| mode | RangeMode | Η λειτουργία εύρους. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |
| splitMode | SplitMode | Η λειτουργία διαίρεσης του [`Mode`](../mode). |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`SplitOptions`](../../splitoptions).

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |
| mode | RangeMode | Η λειτουργία εύρους. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
