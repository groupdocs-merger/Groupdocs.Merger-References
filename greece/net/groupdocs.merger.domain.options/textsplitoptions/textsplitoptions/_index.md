---
title: TextSplitOptions
second_title: GroupDocs.Merger for .NET API Reference
description: Αρχικοποιεί μια νέα παρουσία τουTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία του[`TextSplitOptions`](../../textsplitoptions) τάξη.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη καθορισμένη επέκταση. |
| lineNumbers | Int32[] | Αριθμοί γραμμών για διαχωρισμό κειμένου. |

### Δείτε επίσης

* class [TextSplitOptions](../../textsplitoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία του[`TextSplitOptions`](../../textsplitoptions) τάξη.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη καθορισμένη επέκταση. |
| mode | TextSplitMode | Λειτουργία για διαχωρισμό κειμένου. |
| lineNumbers | Int32[] | Αριθμοί γραμμών για διαχωρισμό κειμένου. |

### Δείτε επίσης

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`TextSplitOptions`](../../textsplitoptions) τάξη.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων διαχωρισμού εξόδου. |
| lineNumbers | Int32[] | Αριθμοί γραμμών για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`TextSplitOptions`](../../textsplitoptions) τάξη.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων διαχωρισμού εξόδου. |
| mode | TextSplitMode | Λειτουργία για διαχωρισμό κειμένου. |
| lineNumbers | Int32[] | Αριθμοί γραμμών για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`TextSplitOptions`](../../textsplitoptions) τάξη.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο createPageStream. |
| lineNumbers | Int32[] | Αριθμοί γραμμών για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`TextSplitOptions`](../../textsplitoptions) τάξη.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο createPageStream. |
| mode | TextSplitMode | Λειτουργία για διαχωρισμό κειμένου. |
| lineNumbers | Int32[] | Αριθμοί γραμμών για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* συνέλευση [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
