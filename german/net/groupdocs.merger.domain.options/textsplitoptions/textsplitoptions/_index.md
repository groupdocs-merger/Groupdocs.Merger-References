---
title: TextSplitOptions
second_title: GroupDocs.Merger für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Initialisiert eine neue Instanz von[`TextSplitOptions`](../../textsplitoptions) Klasse.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'c:/split{0}.doc' oder 'c:/split{0}.{1}' mit bereits definierter Endung. |
| lineNumbers | Int32[] | Zeilennummern für die Textaufteilung. |

### Siehe auch

* class [TextSplitOptions](../../textsplitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Initialisiert eine neue Instanz von[`TextSplitOptions`](../../textsplitoptions) Klasse.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | String | Das Dateipfadformat zB 'c:/split{0}.doc' oder 'c:/split{0}.{1}' mit bereits definierter Endung. |
| mode | TextSplitMode | Modus für die Textaufteilung. |
| lineNumbers | Int32[] | Zeilennummern für die Textaufteilung. |

### Siehe auch

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Initialisiert eine neue Instanz von[`TextSplitOptions`](../../textsplitoptions) Klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| lineNumbers | Int32[] | Zeilennummern für die Textaufteilung. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Initialisiert eine neue Instanz von[`TextSplitOptions`](../../textsplitoptions) Klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| mode | TextSplitMode | Modus für die Textaufteilung. |
| lineNumbers | Int32[] | Zeilennummern für die Textaufteilung. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Initialisiert eine neue Instanz von[`TextSplitOptions`](../../textsplitoptions) Klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| lineNumbers | Int32[] | Zeilennummern für die Textaufteilung. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Montage [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Initialisiert eine neue Instanz von[`TextSplitOptions`](../../textsplitoptions) Klasse.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Die Methode, die den Stream instanziiert, der zum Schreiben von aufgeteilten Ausgabedaten verwendet wird. |
| releaseSplitStream | ReleaseSplitStream | Die Methode, die den von der createPageStream-Methode erstellten Stream freigibt. |
| mode | TextSplitMode | Modus für die Textaufteilung. |
| lineNumbers | Int32[] | Zeilennummern für die Textaufteilung. |

### Siehe auch

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namensraum [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* Montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
