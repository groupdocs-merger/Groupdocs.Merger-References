---
title: TextSplitOptions
second_title: GroupDocs.Merger for .NET API Reference
description: Initializes a new instance of the TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions class.
type: docs
weight: 10
url: /net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Initializes a new instance of the [`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already defined extension. |
| lineNumbers | Int32[] | Line numbers for text splitting. |

### See Also

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Initializes a new instance of the [`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePathFormat | String | The file path format e.g. 'c:/split{0}.doc' or 'c:/split{0}.{1}' with already defined extension. |
| mode | TextSplitMode | Mode for text splitting. |
| lineNumbers | Int32[] | Line numbers for text splitting. |

### See Also

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Initializes a new instance of the [`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| lineNumbers | Int32[] | Line numbers for text splitting. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Initializes a new instance of the [`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| mode | TextSplitMode | Mode for text splitting. |
| lineNumbers | Int32[] | Line numbers for text splitting. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Initializes a new instance of the [`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |
| lineNumbers | Int32[] | Line numbers for text splitting. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Initializes a new instance of the [`TextSplitOptions`](../../textsplitoptions) class.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | The method that instantiates stream used to write output split data. |
| releaseSplitStream | ReleaseSplitStream | The method that releases stream created by createPageStream method. |
| mode | TextSplitMode | Mode for text splitting. |
| lineNumbers | Int32[] | Line numbers for text splitting. |

### See Also

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
