---
title: "Join"
second_title: "GroupDocs.Merger for .NET API 参考"
description: "将多个文档合并为一个文档。"
type: docs
weight: 120
url: /zh/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

将多个文档合并为一个文档。

```csharp
public IMerger Join(Stream document)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 已合并的文档。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

将多个文档合并为一个文档。

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 已合并的文档。 |
| joinOptions | IJoinOptions | 合并选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |
| ArgumentNullException | 当 *joinOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

将多个文档合并为一个文档。

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 已合并的文档。 |
| joinOptions | IPageJoinOptions | 合并选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |
| ArgumentNullException | 当 *joinOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

将多个文档合并为一个文档。

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | 流 | 已合并的文档。 |
| joinOptions | IImageJoinOptions | 图像合并选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *document* 为 null 时抛出。 |
| ArgumentNullException | 当 *joinOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

将多个文档合并为一个文档。

```csharp
public IMerger Join(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 已合并文档的文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

将多个文档合并为一个文档。

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 已合并文档的文件路径。 |
| joinOptions | IJoinOptions | 合并选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *joinOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

将多个文档合并为一个文档。

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 已合并文档的文件路径。 |
| joinOptions | IPageJoinOptions | 合并选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *joinOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

将多个文档合并为一个文档。

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 已合并文档的文件路径。 |
| joinOptions | IImageJoinOptions | 图像合并选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *joinOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 另见

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
