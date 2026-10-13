---
title: "マージャー"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "Mergergroupdocs.merger/merger クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Stream document)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 読み取り可能なストリームです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |

### 関連項目

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 読み取り可能なストリームです。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Stream document, MergerSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 読み取り可能なストリームです。 |
| settings | MergerSettings | このマージ設定。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 関連項目

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | ストリーム | 読み取り可能なストリームです。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。 |
| settings | MergerSettings | このマージ設定。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *document* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Func<Stream> getFileStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| settings | MergerSettings | このマージ設定。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。 |
| settings | MergerSettings | このマージ設定。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *getFileStream* が null のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(string filePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |

### 関連項目

* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(string filePath, MergerSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス。 |
| settings | MergerSettings | このマージ設定。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 関連項目

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

[`Merger`](../../merger) クラスの新しいインスタンスを初期化します。

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ファイルパス。 |
| loadOptions | ILoadOptions | ドキュメントのロードオプションです。 |
| settings | MergerSettings | このマージ設定。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *filePath* が null または空のときにスローされます。 |
| ArgumentNullException | *loadOptions* が null のときにスローされます。 |
| ArgumentNullException | *settings* が null のときにスローされます。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
