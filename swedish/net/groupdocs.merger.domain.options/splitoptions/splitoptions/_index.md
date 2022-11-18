---
title: SplitOptions
second_title: GroupDocs.Merger för .NET API-referens
description: Initierar en ny instans avSplitOptionsgroupdocs.merger.domain.options/splitoptions class.
type: docs
weight: 10
url: /sv/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet t.ex. 'c:/split{0}.doc' eller 'c:/split{0}.{1}' med redan fördefinierat tillägg. |
| pageNumbers | Int32[] | Sidnummer. |

### Se även

* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet t.ex. 'c:/split{0}.doc' eller 'c:/split{0}.{1}' med redan fördefinierat tillägg. |
| pageNumbers | Int32[] | Sidnummer. |
| splitMode | SplitMode | Uppdelningsläget för[`Mode`](../mode). |

### Se även

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet t.ex. 'c:/split{0}.doc' eller 'c:/split{0}.{1}' med redan fördefinierat tillägg. |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |

### Se även

* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet t.ex. 'c:/split{0}.doc' eller 'c:/split{0}.{1}' med redan fördefinierat tillägg. |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |
| mode | RangeMode | Räckviddsläget. |

### Se även

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| pageNumbers | Int32[] | Sidnummer. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| pageNumbers | Int32[] | Sidnummer. |
| splitMode | SplitMode | Uppdelningsläget för[`Mode`](../mode). |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |
| mode | RangeMode | Räckviddsläget. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |
| pageNumbers | Int32[] | Sidnummer. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |
| pageNumbers | Int32[] | Sidnummer. |
| splitMode | SplitMode | Uppdelningsläget för[`Mode`](../mode). |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Initierar en ny instans av[`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |
| mode | RangeMode | Räckviddsläget. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../splitoptions)
* hopsättning [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
