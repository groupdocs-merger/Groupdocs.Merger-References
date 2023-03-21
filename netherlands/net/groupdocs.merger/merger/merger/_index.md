---
title: Merger
second_title: GroupDocs.Merger voor .NET API-referentie
description: Initialiseert nieuw exemplaar vanMergergroupdocs.merger/merger klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De leesbare stroom. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*document* is niets. |

### Zie ook

* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De leesbare stroom. |
| loadOptions | ILoadOptions | De opties voor het laden van documenten. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*document* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |

### Zie ook

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De leesbare stroom. |
| settings | MergerSettings | De fusie-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*document* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Zie ook

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De leesbare stroom. |
| loadOptions | ILoadOptions | De opties voor het laden van documenten. |
| settings | MergerSettings | De fusie-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*document* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Zie ook

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |

### Zie ook

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | ILoadOptions | De opties voor het laden van documenten. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |

### Zie ook

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| settings | MergerSettings | De fusie-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Zie ook

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | ILoadOptions | De opties voor het laden van documenten. |
| settings | MergerSettings | De fusie-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*getFileStream* is niets. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Zie ook

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*filePath* is null of leeg. |

### Zie ook

* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| loadOptions | ILoadOptions | De opties voor het laden van documenten. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*filePath* is null of leeg. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |

### Zie ook

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| settings | MergerSettings | De fusie-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*filePath* is null of leeg. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Zie ook

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Initialiseert nieuw exemplaar van[`Merger`](../../merger) klasse.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad. |
| loadOptions | ILoadOptions | De opties voor het laden van documenten. |
| settings | MergerSettings | De fusie-instellingen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*filePath* is null of leeg. |
| ArgumentNullException | Wanneer gegooid*loadOptions* is niets. |
| ArgumentNullException | Wanneer gegooid*settings* is niets. |

### Zie ook

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* naamruimte [GroupDocs.Merger](../../merger)
* montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
