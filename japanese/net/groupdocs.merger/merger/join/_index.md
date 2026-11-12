---
title: "Join"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "ドキュメントを1つの単一ドキュメントに結合します。"
type: docs
weight: 120
url: /ja/net/groupdocs.merger/merger/join/
---
## Join(Stream) {#join}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(Stream document)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 結合されたドキュメントです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IJoinOptions) {#join_2}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(Stream document, IJoinOptions joinOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 結合されたドキュメントです。 |
| joinOptions | IJoinOptions | 結合オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |
| ArgumentNullException | *joinOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IPageJoinOptions) {#join_3}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(Stream document, IPageJoinOptions joinOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 結合されたドキュメントです。 |
| joinOptions | IPageJoinOptions | 結合オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |
| ArgumentNullException | *joinOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(Stream, IImageJoinOptions) {#join_1}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(Stream document, IImageJoinOptions joinOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 結合されたドキュメントです。 |
| joinOptions | IImageJoinOptions | 画像結合オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |
| ArgumentNullException | *joinOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string) {#join_4}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(string filePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | 結合されたドキュメントのファイルパスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IJoinOptions) {#join_6}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(string filePath, IJoinOptions joinOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | 結合されたドキュメントのファイルパスです。 |
| joinOptions | IJoinOptions | 結合オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *joinOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* interface [IJoinOptions](../../../groupdocs.merger.domain.options/ijoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IPageJoinOptions) {#join_7}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(string filePath, IPageJoinOptions joinOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | 結合されたドキュメントのファイルパスです。 |
| joinOptions | IPageJoinOptions | 結合オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *joinOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* interface [IPageJoinOptions](../../../groupdocs.merger.domain.options/ipagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Join(string, IImageJoinOptions) {#join_5}

ドキュメントを1つの単一ドキュメントに結合します。

```csharp
public IMerger Join(string filePath, IImageJoinOptions joinOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | 結合されたドキュメントのファイルパスです。 |
| joinOptions | IImageJoinOptions | 画像結合オプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *joinOptions* が null のときにスローされます。 |

### 備考

**Learn more**

* More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps](https://docs.groupdocs.com/merger/net/merge-files/)

### 関連項目

* interface [IMerger](../../imerger)
* interface [IImageJoinOptions](../../../groupdocs.merger.domain.options/iimagejoinoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
