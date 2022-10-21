---
title: Merger
second_title: GroupDocs.Merger for .NET API 参考
description: 初始化的新实例Mergergroupdocs.merger/merger类.
type: docs
weight: 10
url: /zh/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Stream document)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 可读流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*document*一片空白。 |

### 也可以看看

* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 可读流。 |
| loadOptions | ILoadOptions | 文档加载选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*document*一片空白。 |
| ArgumentNullException | 何时抛出*loadOptions*一片空白。 |

### 也可以看看

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 可读流。 |
| settings | MergerSettings | 合并设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*document*一片空白。 |
| ArgumentNullException | 何时抛出*settings*一片空白。 |

### 也可以看看

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 可读流。 |
| loadOptions | ILoadOptions | 文档加载选项。 |
| settings | MergerSettings | 合并设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*document*一片空白。 |
| ArgumentNullException | 何时抛出*loadOptions*一片空白。 |
| ArgumentNullException | 何时抛出*settings*一片空白。 |

### 也可以看看

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Func<Stream> getFileStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*getFileStream*一片空白。 |

### 也可以看看

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| loadOptions | ILoadOptions | 文档加载选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*getFileStream*一片空白。 |
| ArgumentNullException | 何时抛出*loadOptions*一片空白。 |

### 也可以看看

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| settings | MergerSettings | 合并设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*getFileStream*一片空白。 |
| ArgumentNullException | 何时抛出*settings*一片空白。 |

### 也可以看看

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| loadOptions | ILoadOptions | 文档加载选项。 |
| settings | MergerSettings | 合并设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*getFileStream*一片空白。 |
| ArgumentNullException | 何时抛出*loadOptions*一片空白。 |
| ArgumentNullException | 何时抛出*settings*一片空白。 |

### 也可以看看

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*filePath*为空或为空。 |

### 也可以看看

* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | ILoadOptions | 文档加载选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*filePath*为空或为空。 |
| ArgumentNullException | 何时抛出*loadOptions*一片空白。 |

### 也可以看看

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| settings | MergerSettings | 合并设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*filePath*为空或为空。 |
| ArgumentNullException | 何时抛出*settings*一片空白。 |

### 也可以看看

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

初始化的新实例[`Merger`](../../merger)类.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | ILoadOptions | 文档加载选项。 |
| settings | MergerSettings | 合并设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*filePath*为空或为空。 |
| ArgumentNullException | 何时抛出*loadOptions*一片空白。 |
| ArgumentNullException | 何时抛出*settings*一片空白。 |

### 也可以看看

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 命名空间 [GroupDocs.Merger](../../merger)
* 部件 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
