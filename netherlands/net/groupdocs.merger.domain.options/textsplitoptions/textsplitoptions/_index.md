---
title: TextSplitOptions
second_title: GroupDocs.Merger voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Initialiseert een nieuw exemplaar van het[`TextSplitOptions`](../../textsplitoptions) klasse.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'c:/split{0}.doc' of 'c:/split{0}.{1}' met een reeds gedefinieerde extensie. |
| lineNumbers | Int32[] | Regelnummers voor het splitsen van tekst. |

### Zie ook

* class [TextSplitOptions](../../textsplitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Initialiseert een nieuw exemplaar van het[`TextSplitOptions`](../../textsplitoptions) klasse.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | String | De indeling van het bestandspad, bijvoorbeeld 'c:/split{0}.doc' of 'c:/split{0}.{1}' met een reeds gedefinieerde extensie. |
| mode | TextSplitMode | Modus voor het splitsen van tekst. |
| lineNumbers | Int32[] | Regelnummers voor het splitsen van tekst. |

### Zie ook

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`TextSplitOptions`](../../textsplitoptions) klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| lineNumbers | Int32[] | Regelnummers voor het splitsen van tekst. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`TextSplitOptions`](../../textsplitoptions) klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| mode | TextSplitMode | Modus voor het splitsen van tekst. |
| lineNumbers | Int32[] | Regelnummers voor het splitsen van tekst. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`TextSplitOptions`](../../textsplitoptions) klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |
| lineNumbers | Int32[] | Regelnummers voor het splitsen van tekst. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Initialiseert een nieuw exemplaar van het[`TextSplitOptions`](../../textsplitoptions) klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | De methode die de stream instantiseert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| releaseSplitStream | ReleaseSplitStream | De methode die stream vrijgeeft die is gemaakt met de methode createPageStream. |
| mode | TextSplitMode | Modus voor het splitsen van tekst. |
| lineNumbers | Int32[] | Regelnummers voor het splitsen van tekst. |

### Zie ook

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* naamruimte [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
