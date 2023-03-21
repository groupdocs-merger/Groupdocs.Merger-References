---
title: SplitOptions
second_title: GroupDocs.Merger for .NET API リファレンス
description: の新しいインスタンスを初期化しますSplitOptionsgroupdocs.merger.domain.options/splitoptionsclass.
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイル パス形式 (例: 'c:/split{0}.doc' または 'c:/split{0}.{1}' など、事前に定義された拡張子付き)。 |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイル パス形式 (例: 'c:/split{0}.doc' または 'c:/split{0}.{1}' など、事前に定義された拡張子付き)。 |
| pageNumbers | Int32[] | ページ番号。 |
| splitMode | SplitMode | の分割モード[`Mode`](../mode). |

### 関連項目

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイル パス形式 (例: 'c:/split{0}.doc' または 'c:/split{0}.{1}' など、事前に定義された拡張子付き)。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイル パス形式 (例: 'c:/split{0}.doc' または 'c:/split{0}.{1}' など、事前に定義された拡張子付き)。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |
| splitMode | SplitMode | の分割モード[`Mode`](../mode). |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| pageNumbers | Int32[] | ページ番号。 |
| splitMode | SplitMode | の分割モード[`Mode`](../mode). |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

の新しいインスタンスを初期化します[`SplitOptions`](../../splitoptions)class.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../splitoptions)
* 組み立て [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
