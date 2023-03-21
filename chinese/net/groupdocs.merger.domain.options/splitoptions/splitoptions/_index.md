---
title: SplitOptions
second_title: GroupDocs.Merger for .NET API 参考
description: 初始化一个新的实例SplitOptionsgroupdocs.merger.domain.options/splitoptions类.
type: docs
weight: 10
url: /zh/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}' 已预定义扩展名。 |
| pageNumbers | Int32[] | 页码。 |

### 也可以看看

* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}' 已预定义扩展名。 |
| pageNumbers | Int32[] | 页码。 |
| splitMode | SplitMode | 的分裂模式[`Mode`](../mode). |

### 也可以看看

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}' 已预定义扩展名。 |
| startNumber | Int32 | 起始页码。 |
| endNumber | Int32 | 结束页码。 |

### 也可以看看

* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'c:/split{0}.doc' 或 'c:/split{0}.{1}' 已预定义扩展名。 |
| startNumber | Int32 | 起始页码。 |
| endNumber | Int32 | 结束页码。 |
| mode | RangeMode | 范围模式。 |

### 也可以看看

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| pageNumbers | Int32[] | 页码。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| pageNumbers | Int32[] | 页码。 |
| splitMode | SplitMode | 的分裂模式[`Mode`](../mode). |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| startNumber | Int32 | 起始页码。 |
| endNumber | Int32 | 结束页码。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| startNumber | Int32 | 起始页码。 |
| endNumber | Int32 | 结束页码。 |
| mode | RangeMode | 范围模式。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放通过 createPageStream 方法创建的流的方法。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放通过 createPageStream 方法创建的流的方法。 |
| pageNumbers | Int32[] | 页码。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放通过 createPageStream 方法创建的流的方法。 |
| pageNumbers | Int32[] | 页码。 |
| splitMode | SplitMode | 的分裂模式[`Mode`](../mode). |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放通过 createPageStream 方法创建的流的方法。 |
| startNumber | Int32 | 起始页码。 |
| endNumber | Int32 | 结束页码。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

初始化一个新的实例[`SplitOptions`](../../splitoptions)类.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 实例化用于写入输出拆分数据的流的方法。 |
| releaseSplitStream | ReleaseSplitStream | 释放通过 createPageStream 方法创建的流的方法。 |
| startNumber | Int32 | 起始页码。 |
| endNumber | Int32 | 结束页码。 |
| mode | RangeMode | 范围模式。 |

### 也可以看看

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 部件 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
