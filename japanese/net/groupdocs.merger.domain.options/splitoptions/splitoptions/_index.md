---
title: "SplitOptions"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "SplitOptionsgroupdocs.merger.domain.options/splitoptions クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパスの形式（例: 'c:/split{0}.doc' または 'c:/split{0}.{1}'）で、既に事前定義された拡張子が使用されます。 |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパスの形式（例: 'c:/split{0}.doc' または 'c:/split{0}.{1}'）で、既に事前定義された拡張子が使用されます。 |
| pageNumbers | Int32[] | ページ番号。 |
| splitMode | SplitMode | [`Mode`](../mode) の分割モードです。 |

### 関連項目

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパスの形式（例: 'c:/split{0}.doc' または 'c:/split{0}.{1}'）で、既に事前定義された拡張子が使用されます。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイルパスの形式（例: 'c:/split{0}.doc' または 'c:/split{0}.{1}'）で、既に事前定義された拡張子が使用されます。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |
| splitMode | SplitMode | [`Mode`](../mode) の分割モードです。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |
| splitMode | SplitMode | [`Mode`](../mode) の分割モードです。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

[`SplitOptions`](../../splitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
