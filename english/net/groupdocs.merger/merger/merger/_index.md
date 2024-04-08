---
title: Merger
second_title: GroupDocs.Merger for .NET API Reference
description: Initializes new instance of Mergergroupdocs.merger/merger class.
type: docs
weight: 10
url: /net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Stream document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The readable stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *document* is null. |

### See Also

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The readable stream. |
| loadOptions | ILoadOptions | The document load options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *document* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |

### See Also

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The readable stream. |
| settings | MergerSettings | The Merger settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *document* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### See Also

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The readable stream. |
| loadOptions | ILoadOptions | The document load options. |
| settings | MergerSettings | The Merger settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *document* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### See Also

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |

### See Also

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |
| loadOptions | ILoadOptions | The document load options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |

### See Also

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |
| settings | MergerSettings | The Merger settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### See Also

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |
| loadOptions | ILoadOptions | The document load options. |
| settings | MergerSettings | The Merger settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### See Also

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *filePath* is null or empty. |

### See Also

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| loadOptions | ILoadOptions | The document load options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *loadOptions* is null. |

### See Also

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| settings | MergerSettings | The Merger settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *settings* is null. |

### See Also

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Initializes new instance of [`Merger`](../../merger) class.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| loadOptions | ILoadOptions | The document load options. |
| settings | MergerSettings | The Merger settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *loadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### See Also

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
