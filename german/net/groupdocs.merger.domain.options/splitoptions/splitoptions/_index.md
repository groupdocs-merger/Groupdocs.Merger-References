---
title: SplitOptions
second_title: GroupDocs.Merger für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonSplitOptionsgroupdocs.merger.domain.options/splitoptions Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'c:/split{0}.doc' oder 'c:/split{0}.{1}' mit bereits vordefinierter Endung. |
| pageNumbers | Int32[] | Seitenzahlen. |

### Siehe auch

* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'c:/split{0}.doc' oder 'c:/split{0}.{1}' mit bereits vordefinierter Endung. |
| pageNumbers | Int32[] | Seitenzahlen. |
| splitMode | SplitMode | Der Aufteilungsmodus von[`Mode`](../mode). |

### Siehe auch

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'c:/split{0}.doc' oder 'c:/split{0}.{1}' mit bereits vordefinierter Endung. |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |

### Siehe auch

* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'c:/split{0}.doc' oder 'c:/split{0}.{1}' mit bereits vordefinierter Endung. |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |
| mode | RangeMode | Der Reichweitenmodus. |

### Siehe auch

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| pageNumbers | Int32[] | Seitenzahlen. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| pageNumbers | Int32[] | Seitenzahlen. |
| splitMode | SplitMode | Der Aufteilungsmodus von[`Mode`](../mode). |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |
| mode | RangeMode | Der Reichweitenmodus. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| pageNumbers | Int32[] | Seitenzahlen. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| pageNumbers | Int32[] | Seitenzahlen. |
| splitMode | SplitMode | Der Aufteilungsmodus von[`Mode`](../mode). |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Initialisiert eine neue Instanz von[`SplitOptions`](../../splitoptions) Klasse.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |
| mode | RangeMode | Der Reichweitenmodus. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../splitoptions)
* Montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
