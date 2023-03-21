---
title: Merger
second_title: GroupDocs.Merger for .NET API リファレンス
description: の新しいインスタンスを初期化しますMergergroupdocs.merger/mergerclass.
type: docs
weight: 10
url: /ja/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Stream document)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 読み取り可能なストリーム。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*document*無効である。 |

### 関連項目

* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 読み取り可能なストリーム。 |
| loadOptions | ILoadOptions | ドキュメントの読み込みオプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*document*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 読み取り可能なストリーム。 |
| settings | MergerSettings | 合併の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*document*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 関連項目

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Stream | 読み取り可能なストリーム。 |
| loadOptions | ILoadOptions | ドキュメントの読み込みオプション。 |
| settings | MergerSettings | 合併の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*document*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Func<Stream> getFileStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | ILoadOptions | ドキュメントの読み込みオプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| settings | MergerSettings | 合併の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| getFileStream | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | ILoadOptions | ドキュメントの読み込みオプション。 |
| settings | MergerSettings | 合併の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*getFileStream*無効である。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 関連項目

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*filePath* null または空です。 |

### 関連項目

* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |
| loadOptions | ILoadOptions | ドキュメントの読み込みオプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*filePath* null または空です。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |
| settings | MergerSettings | 合併の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*filePath* null または空です。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 関連項目

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

の新しいインスタンスを初期化します[`Merger`](../../merger)class.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ファイル パス。 |
| loadOptions | ILoadOptions | ドキュメントの読み込みオプション。 |
| settings | MergerSettings | 合併の設定。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*filePath* null または空です。 |
| ArgumentNullException | スローされるタイミング*loadOptions*無効である。 |
| ArgumentNullException | スローされるタイミング*settings*無効である。 |

### 関連項目

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* 名前空間 [GroupDocs.Merger](../../merger)
* 組み立て [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
