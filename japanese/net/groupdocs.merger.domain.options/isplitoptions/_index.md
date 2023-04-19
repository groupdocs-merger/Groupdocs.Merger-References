---
title: ISplitOptions
second_title: GroupDocs.Merger for .NET API リファレンス
description: ページ分割オプションのインターフェイス
type: docs
weight: 340
url: /ja/net/groupdocs.merger.domain.options/isplitoptions/
---
## ISplitOptions interface

ページ分割オプションのインターフェイス。

```csharp
public interface ISplitOptions : IPageOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CreateStream](../../groupdocs.merger.domain.options/isplitoptions/createstream) { get; } | 出力分割ストリームを作成するメソッドを定義するデリゲート。 |
| [Mode](../../groupdocs.merger.domain.options/isplitoptions/mode) { get; } | ページ分割のモードを取得します。 |
| [ReleaseStream](../../groupdocs.merger.domain.options/isplitoptions/releasestream) { get; } | 出力分割ストリームを解放するメソッドを定義するデリゲート。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetPathByIndex](../../groupdocs.merger.domain.options/isplitoptions/getpathbyindex)(int, string) | 定義された拡張子を持つインデックスによって分割されたドキュメントの完全なファイル パスを取得します。 |
| [Validate](../../groupdocs.merger.domain.options/isplitoptions/validate)(FileType) | 分割オプションを検証します。 |

### 関連項目

* interface [IPageOptions](../ipageoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* 組み立て [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->