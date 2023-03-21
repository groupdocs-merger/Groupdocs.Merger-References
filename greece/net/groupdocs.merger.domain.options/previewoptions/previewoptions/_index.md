---
title: PreviewOptions
second_title: GroupDocs.Merger for .NET API Reference
description: Αρχικοποιεί μια νέα παρουσία τουPreviewOptionsgroupdocs.merger.domain.options/previewoptions τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |
| startNumber | Int32 | Ο αριθμός της αρχικής σελίδας. |
| endNumber | Int32 | Ο αριθμός της τελικής σελίδας. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |
| startNumber | Int32 | Ο αριθμός της αρχικής σελίδας. |
| endNumber | Int32 | Ο αριθμός της τελικής σελίδας. |
| mode | RangeMode | Η λειτουργία εμβέλειας. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |
| startNumber | Int32 | Ο αριθμός της αρχικής σελίδας. |
| endNumber | Int32 | Ο αριθμός της τελικής σελίδας. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία του[`PreviewOptions`](../../previewoptions) τάξη.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί τη ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε με τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του[`Mode`](../mode) |
| startNumber | Int32 | Ο αριθμός της αρχικής σελίδας. |
| endNumber | Int32 | Ο αριθμός της τελικής σελίδας. |
| mode | RangeMode | Η λειτουργία εμβέλειας. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Options](../../previewoptions)
* συνέλευση [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
