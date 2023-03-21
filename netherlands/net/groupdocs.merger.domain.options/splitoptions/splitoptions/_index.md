---
title: SplitOptions
second_title: GroupDocs.Merger voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetSplitOptionsgroupdocs.merger.domain.options/splitoptions klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'c:/split{0}.doc' of 'c:/split{0}.{1}' met een vooraf gedefinieerde extensie. |
| pageNumbers | Int32[] | Paginanummers. |

### Zie ook

* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'c:/split{0}.doc' of 'c:/split{0}.{1}' met een vooraf gedefinieerde extensie. |
| pageNumbers | Int32[] | Paginanummers. |
| splitMode | SplitMode | De splitsingsmodus van[`Mode`](../mode). |

### Zie ook

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'c:/split{0}.doc' of 'c:/split{0}.{1}' met een vooraf gedefinieerde extensie. |
| startNumber | Int32 | Het startpaginanummer. |
| endNumber | Int32 | Het eindpaginanummer. |

### Zie ook

* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'c:/split{0}.doc' of 'c:/split{0}.{1}' met een vooraf gedefinieerde extensie. |
| startNumber | Int32 | Het startpaginanummer. |
| endNumber | Int32 | Het eindpaginanummer. |
| mode | RangeMode | De bereikmodus. |

### Zie ook

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| pageNumbers | Int32[] | Paginanummers. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| pageNumbers | Int32[] | Paginanummers. |
| splitMode | SplitMode | De splitsingsmodus van[`Mode`](../mode). |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| startNumber | Int32 | Het startpaginanummer. |
| endNumber | Int32 | Het eindpaginanummer. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| startNumber | Int32 | Het startpaginanummer. |
| endNumber | Int32 | Het eindpaginanummer. |
| mode | RangeMode | De bereikmodus. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |
| pageNumbers | Int32[] | Paginanummers. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |
| pageNumbers | Int32[] | Paginanummers. |
| splitMode | SplitMode | De splitsingsmodus van[`Mode`](../mode). |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |
| startNumber | Int32 | Het startpaginanummer. |
| endNumber | Int32 | Het eindpaginanummer. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`SplitOptions`](../../splitoptions) klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |
| startNumber | Int32 | Het startpaginanummer. |
| endNumber | Int32 | Het eindpaginanummer. |
| mode | RangeMode | De bereikmodus. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../splitoptions)
* montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
