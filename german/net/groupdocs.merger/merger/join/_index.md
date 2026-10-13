---
title: "Join"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Fügt die Dokumente zu einem einzigen Dokument zusammen."
type: docs
weight: 120
url: /de/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Zusammengeführtes Dokument. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Zusammengeführtes Dokument. |
| joinOptions | IJoinOptions | Die Join-Optionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *joinOptions* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Zusammengeführtes Dokument. |
| joinOptions | IPageJoinOptions | Die Join-Optionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *joinOptions* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Zusammengeführtes Dokument. |
| joinOptions | IImageJoinOptions | Die Bild‑Zusammenführungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *document* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *joinOptions* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Dateipfad des zusammengeführten Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Dateipfad des zusammengeführten Dokuments. |
| joinOptions | IJoinOptions | Die Join-Optionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *joinOptions* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Dateipfad des zusammengeführten Dokuments. |
| joinOptions | IPageJoinOptions | Die Join-Optionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *joinOptions* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

Fügt die Dokumente zu einem einzigen Dokument zusammen.

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Dateipfad des zusammengeführten Dokuments. |
| joinOptions | IImageJoinOptions | Die Bild‑Zusammenführungsoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *joinOptions* null ist. |

### Bemerkungen

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### Siehe auch

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
