---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "TextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

[`TextSplitOptions`](../../textsplitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイル パス形式（例: 'c:/split{0}.doc' または 'c:/split{0}.{1}'）は、既に定義された拡張子を使用します。 |
| lineNumbers | Int32[] | テキスト分割用の行番号。 |

### 関連項目

* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

[`TextSplitOptions`](../../textsplitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | String | ファイル パス形式（例: 'c:/split{0}.doc' または 'c:/split{0}.{1}'）は、既に定義された拡張子を使用します。 |
| mode | TextSplitMode | テキスト分割モード。 |
| lineNumbers | Int32[] | テキスト分割用の行番号。 |

### 関連項目

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

[`TextSplitOptions`](../../textsplitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| lineNumbers | Int32[] | テキスト分割用の行番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

[`TextSplitOptions`](../../textsplitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| mode | TextSplitMode | テキスト分割モード。 |
| lineNumbers | Int32[] | テキスト分割用の行番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

[`TextSplitOptions`](../../textsplitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| lineNumbers | Int32[] | テキスト分割用の行番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

[`TextSplitOptions`](../../textsplitoptions) クラスの新しいインスタンスを初期化します。

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releaseSplitStream | ReleaseSplitStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| mode | TextSplitMode | テキスト分割モード。 |
| lineNumbers | Int32[] | テキスト分割用の行番号。 |

### 関連項目

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
