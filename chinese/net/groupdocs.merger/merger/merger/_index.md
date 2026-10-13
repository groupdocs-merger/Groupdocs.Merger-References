---
title: "合并器"
second_title: "GroupDocs.Merger for .NET API 参考"
description: "初始化 Mergergroupdocs.merger/merger 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Stream document)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 可读取的流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |

### 另见

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 可读取的流。 |
| loadOptions | ILoadOptions | 文档加载选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |

### 另见

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Stream document, MergerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 可读取的流。 |
| settings | MergerSettings | Merger 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 另见

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 可读取的流。 |
| loadOptions | ILoadOptions | 文档加载选项。 |
| settings | MergerSettings | Merger 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 另见

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Func<Stream> getFileStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |

### 另见

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| loadOptions | ILoadOptions | 文档加载选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |

### 另见

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| settings | MergerSettings | Merger 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 另见

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| loadOptions | ILoadOptions | 文档加载选项。 |
| settings | MergerSettings | Merger 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 另见

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |

### 另见

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | ILoadOptions | 文档加载选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |

### 另见

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(string filePath, MergerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| settings | MergerSettings | Merger 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 另见

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

初始化 [`Merger`](../../merger) 类的新实例。

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |
| loadOptions | ILoadOptions | 文档加载选项。 |
| settings | MergerSettings | Merger 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 另见

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
