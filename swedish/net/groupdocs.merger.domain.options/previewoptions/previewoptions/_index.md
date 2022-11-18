---
title: PreviewOptions
second_title: GroupDocs.Merger för .NET API-referens
description: Initierar en ny instans avPreviewOptionsgroupdocs.merger.domain.options/previewoptions class.
type: docs
weight: 10
url: /sv/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |
| pageNumbers | Int32[] | Sidnummer. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |
| mode | RangeMode | Räckviddsläget. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| releasePageStream | ReleasePageStream | Metoden som släpper ström skapad av metoden createPageStream. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| releasePageStream | ReleasePageStream | Metoden som släpper ström skapad av metoden createPageStream. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |
| pageNumbers | Int32[] | Sidnummer. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| releasePageStream | ReleasePageStream | Metoden som släpper ström skapad av metoden createPageStream. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Initierar en ny instans av[`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createPageStream | CreatePageStream | Metoden som instansierar ström som används för att skriva utdatasida. |
| releasePageStream | ReleasePageStream | Metoden som släpper ström skapad av metoden createPageStream. |
| previewMode | PreviewMode | Förhandsgranskningsläget för[`Mode`](../mode) |
| startNumber | Int32 | Startsidans nummer. |
| endNumber | Int32 | Slutsidans nummer. |
| mode | RangeMode | Räckviddsläget. |

### Se även

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../previewoptions)
* hopsättning [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
