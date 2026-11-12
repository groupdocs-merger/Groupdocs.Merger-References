---
title: "PreviewOptions"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "PreviewOptionsgroupdocs.merger.domain.options/previewoptions クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

[`PreviewOptions`](../../previewoptions) クラスの新しいインスタンスを初期化します。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドによって作成されたストリームを解放するメソッド。 |
| previewMode | PreviewMode | [`Mode`](../mode) のプレビュー モード |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
