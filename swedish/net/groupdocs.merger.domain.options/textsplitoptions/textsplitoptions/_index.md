---
title: TextSplitOptions
second_title: GroupDocs.Merger för .NET API-referens
description: Initierar en ny instans avTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions class.
type: docs
weight: 10
url: /sv/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Initierar en ny instans av[`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet t.ex. 'c:/split{0}.doc' eller 'c:/split{0}.{1}' med redan definierat tillägg. |
| lineNumbers | Int32[] | Radnummer för textdelning. |

### Se även

* class [TextSplitOptions](../../textsplitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Initierar en ny instans av[`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | String | Filsökvägsformatet t.ex. 'c:/split{0}.doc' eller 'c:/split{0}.{1}' med redan definierat tillägg. |
| mode | TextSplitMode | Läge för textdelning. |
| lineNumbers | Int32[] | Radnummer för textdelning. |

### Se även

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Initierar en ny instans av[`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| lineNumbers | Int32[] | Radnummer för textdelning. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Initierar en ny instans av[`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| mode | TextSplitMode | Läge för textdelning. |
| lineNumbers | Int32[] | Radnummer för textdelning. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Initierar en ny instans av[`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |
| lineNumbers | Int32[] | Radnummer för textdelning. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* hopsättning [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Initierar en ny instans av[`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Metoden som instansierar ström som används för att skriva utdata delad data. |
| releaseSplitStream | ReleaseSplitStream | Metoden som släpper ström skapad av metoden createPageStream. |
| mode | TextSplitMode | Läge för textdelning. |
| lineNumbers | Int32[] | Radnummer för textdelning. |

### Se även

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namnutrymme [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* hopsättning [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
