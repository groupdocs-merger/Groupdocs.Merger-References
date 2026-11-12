---
title: "PreviewOptions"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης PreviewOptionsgroupdocs.merger.domain.options/previewoptions."
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |
| mode | RangeMode | Η λειτουργία εύρους. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |
| pageNumbers | Int32[] | Αριθμοί σελίδων. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`PreviewOptions`](../../previewoptions).

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| createPageStream | CreatePageStream | Η μέθοδος που δημιουργεί το stream που χρησιμοποιείται για την εγγραφή των δεδομένων της εξόδου σελίδας. |
| releasePageStream | ReleasePageStream | Η μέθοδος που απελευθερώνει τη ροή που δημιουργήθηκε από τη μέθοδο createPageStream. |
| previewMode | PreviewMode | Η λειτουργία προεπισκόπησης του [`Mode`](../mode). |
| startNumber | Int32 | Ο αριθμός εκκίνησης της σελίδας. |
| endNumber | Int32 | Ο αριθμός λήξης της σελίδας. |
| mode | RangeMode | Η λειτουργία εύρους. |

### Δείτε επίσης

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
