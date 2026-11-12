---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Δημιουργεί μια νέα παρουσία της κλάσης TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions."
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Δημιουργεί μια νέα παρουσία της κλάσης [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη καθορισμένη επέκταση. |
| lineNumbers | Int32[] | Αριθμοί γραμμής για διαχωρισμό κειμένου. |

### Δείτε επίσης

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Δημιουργεί μια νέα παρουσία της κλάσης [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePathFormat | String | Η μορφή διαδρομής αρχείου π.χ. 'c:/split{0}.doc' ή 'c:/split{0}.{1}' με ήδη καθορισμένη επέκταση. |
| mode | TextSplitMode | Λειτουργία για διαχωρισμό κειμένου. |
| lineNumbers | Int32[] | Αριθμοί γραμμής για διαχωρισμό κειμένου. |

### Δείτε επίσης

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Δημιουργεί μια νέα παρουσία της κλάσης [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| lineNumbers | Int32[] | Αριθμοί γραμμής για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Δημιουργεί μια νέα παρουσία της κλάσης [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| mode | TextSplitMode | Λειτουργία για διαχωρισμό κειμένου. |
| lineNumbers | Int32[] | Αριθμοί γραμμής για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Δημιουργεί μια νέα παρουσία της κλάσης [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| lineNumbers | Int32[] | Αριθμοί γραμμής για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Δημιουργεί μια νέα παρουσία της κλάσης [`TextSplitOptions`](../../textsplitoptions).

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή των δεδομένων διαχωρισμού εξόδου. |
| releaseSplitStream | ReleaseSplitStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| mode | TextSplitMode | Λειτουργία για διαχωρισμό κειμένου. |
| lineNumbers | Int32[] | Αριθμοί γραμμής για διαχωρισμό κειμένου. |

### Δείτε επίσης

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
