---
title: PreviewOptions
second_title: GroupDocs.Merger for .NET API Reference
description: Initializes a new instance of the PreviewOptionsgroupdocs.merger.domain.options/previewoptions class.
type: docs
weight: 10
url: /net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |
| pageNumbers | Int32[] | Page numbers. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |
| mode | RangeMode | The range mode. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| releasePageStream | ReleasePageStream | The method that releases stream created by createPageStream method. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| releasePageStream | ReleasePageStream | The method that releases stream created by createPageStream method. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |
| pageNumbers | Int32[] | Page numbers. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| releasePageStream | ReleasePageStream | The method that releases stream created by createPageStream method. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Initializes a new instance of the [`PreviewOptions`](../../previewoptions) class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Parameter | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | The method that instantiates stream used to write output page data. |
| releasePageStream | ReleasePageStream | The method that releases stream created by createPageStream method. |
| previewMode | PreviewMode | The preview mode of [`Mode`](../mode) |
| startNumber | Int32 | The start page number. |
| endNumber | Int32 | The end page number. |
| mode | RangeMode | The range mode. |

### See Also

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
