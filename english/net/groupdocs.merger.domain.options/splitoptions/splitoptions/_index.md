---
title: SplitOptions
second_title: GroupDocs.Merger for .NET API Reference
description: Initializes a new instance of the SplitOptionsgroupdocs.merger.domain.options/splitoptions class.
type: docs
weight: 10
url: /net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| pageNumbers | Int32[] | Page numbers. |

### See Also

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| pageNumbers | Int32[] | Page numbers. |
| splitMode | SplitMode | The splitting mode of [`Mode`](../mode). |

### See Also

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |

### See Also

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already pre-defined extension. |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |
| mode | RangeMode | The range mode. |

### See Also

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| pageNumbers | Int32[] | Page numbers. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| pageNumbers | Int32[] | Page numbers. |
| splitMode | SplitMode | The splitting mode of [`Mode`](../mode). |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |
| mode | RangeMode | The range mode. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |
| pageNumbers | Int32[] | Page numbers. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |
| pageNumbers | Int32[] | Page numbers. |
| splitMode | SplitMode | The splitting mode of [`Mode`](../mode). |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Initializes a new instance of the [`SplitOptions`](../../splitoptions) class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |
| mode | RangeMode | The range mode. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../splitoptions)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
