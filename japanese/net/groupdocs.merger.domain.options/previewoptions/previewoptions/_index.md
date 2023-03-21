---
title: PreviewOptions
second_title: GroupDocs.Merger for .NET API リファレンス
description: の新しいインスタンスを初期化しますPreviewOptionsgroupdocs.merger.domain.options/previewoptionsclass.
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |
| pageNumbers | Int32[] | ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

の新しいインスタンスを初期化します[`PreviewOptions`](../../previewoptions)class.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 出力ページ データの書き込みに使用されるストリームをインスタンス化するメソッド。 |
| releasePageStream | ReleasePageStream | createPageStream メソッドで作成したストリームを解放するメソッド。 |
| previewMode | PreviewMode | のプレビューモード[`Mode`](../mode) |
| startNumber | Int32 | 開始ページ番号。 |
| endNumber | Int32 | 終了ページ番号。 |
| mode | RangeMode | 範囲モード。 |

### 関連項目

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../previewoptions)
* 組み立て [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
