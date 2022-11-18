---
title: Merger
second_title: GroupDocs.Merger för .NET API-referens
description: Initierar ny instans avMergergroupdocs.merger/merger class.
type: docs
weight: 10
url: /sv/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Stream document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Den läsbara strömmen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*document* är inget. |

### Se även

* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Den läsbara strömmen. |
| loadOptions | ILoadOptions | Alternativen för dokumentladdning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*document* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |

### Se även

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Den läsbara strömmen. |
| settings | MergerSettings | Sammanslagningsinställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*document* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Se även

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Den läsbara strömmen. |
| loadOptions | ILoadOptions | Alternativen för dokumentladdning. |
| settings | MergerSettings | Sammanslagningsinställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*document* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Se även

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |

### Se även

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |
| loadOptions | ILoadOptions | Alternativen för dokumentladdning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |

### Se även

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |
| settings | MergerSettings | Sammanslagningsinställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Se även

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar läsbar ström. |
| loadOptions | ILoadOptions | Alternativen för dokumentladdning. |
| settings | MergerSettings | Sammanslagningsinställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*getFileStream* är inget. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Se även

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*filePath* är null eller tom. |

### Se även

* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| loadOptions | ILoadOptions | Alternativen för dokumentladdning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*filePath* är null eller tom. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |

### Se även

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| settings | MergerSettings | Sammanslagningsinställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*filePath* är null eller tom. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Se även

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Initierar ny instans av[`Merger`](../../merger) class.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen. |
| loadOptions | ILoadOptions | Alternativen för dokumentladdning. |
| settings | MergerSettings | Sammanslagningsinställningarna. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*filePath* är null eller tom. |
| ArgumentNullException | Kastas när*loadOptions* är inget. |
| ArgumentNullException | Kastas när*settings* är inget. |

### Se även

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namnutrymme [GroupDocs.Merger](../../merger)
* hopsättning [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
