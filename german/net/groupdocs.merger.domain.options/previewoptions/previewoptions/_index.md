---
title: PreviewOptions
second_title: GroupDocs.Merger für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonPreviewOptionsgroupdocs.merger.domain.options/previewoptions Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |
| pageNumbers | Int32[] | Seitenzahlen. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |
| mode | RangeMode | Der Reichweitenmodus. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| releasePageStream | ReleasePageStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| releasePageStream | ReleasePageStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |
| pageNumbers | Int32[] | Seitenzahlen. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| releasePageStream | ReleasePageStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Initialisiert eine neue Instanz von[`PreviewOptions`](../../previewoptions) Klasse.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createPageStream | CreatePageStream | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| releasePageStream | ReleasePageStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| previewMode | PreviewMode | Der Vorschaumodus von[`Mode`](../mode) |
| startNumber | Int32 | Die Startseitennummer. |
| endNumber | Int32 | Die letzte Seitenzahl. |
| mode | RangeMode | Der Reichweitenmodus. |

### Siehe auch

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../previewoptions)
* Montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
