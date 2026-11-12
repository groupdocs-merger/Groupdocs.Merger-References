---
title: "PreviewOptions"
second_title: "GroupDocs.Merger for .NET API 参考"
description: "初始化 PreviewOptionsgroupdocs.merger.domain.options/previewoptions 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |
| pageNumbers | Int32[] | 页面编号。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |
| mode | RangeMode | 范围模式。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| releasePageStream | ReleasePageStream | 释放由 createPageStream 方法创建的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| releasePageStream | ReleasePageStream | 释放由 createPageStream 方法创建的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |
| pageNumbers | Int32[] | 页面编号。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| releasePageStream | ReleasePageStream | 释放由 createPageStream 方法创建的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

初始化 [`PreviewOptions`](../../previewoptions) 类的新实例。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| releasePageStream | ReleasePageStream | 释放由 createPageStream 方法创建的流的方法。 |
| previewMode | PreviewMode | [`Mode`](../mode) 的预览模式。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |
| mode | RangeMode | 范围模式。 |

### 另见

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
