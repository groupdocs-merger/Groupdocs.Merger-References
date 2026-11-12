---
title: "SplitOptions"
second_title: "GroupDocs.Merger for .NET API 参考"
description: "初始化 SplitOptionsgroupdocs.merger.domain.options/splitoptions 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}'，已预定义扩展名。 |
| pageNumbers | Int32[] | 页面编号。 |

### 另见

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}'，已预定义扩展名。 |
| pageNumbers | Int32[] | 页面编号。 |
| splitMode | SplitMode | [`Mode`](../mode) 的拆分模式。 |

### 另见

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}'，已预定义扩展名。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |

### 另见

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}'，已预定义扩展名。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |
| mode | RangeMode | 范围模式。 |

### 另见

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| pageNumbers | Int32[] | 页面编号。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| pageNumbers | Int32[] | 页面编号。 |
| splitMode | SplitMode | [`Mode`](../mode) 的拆分模式。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |
| mode | RangeMode | 范围模式。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放由 createPageStream 方法创建的流的方法。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放由 createPageStream 方法创建的流的方法。 |
| pageNumbers | Int32[] | 页面编号。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放由 createPageStream 方法创建的流的方法。 |
| pageNumbers | Int32[] | 页面编号。 |
| splitMode | SplitMode | [`Mode`](../mode) 的拆分模式。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放由 createPageStream 方法创建的流的方法。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

初始化 [`SplitOptions`](../../splitoptions) 类的新实例。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放由 createPageStream 方法创建的流的方法。 |
| startNumber | Int32 | 起始页面编号。 |
| endNumber | Int32 | 结束页面编号。 |
| mode | RangeMode | 范围模式。 |

### 另见

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
