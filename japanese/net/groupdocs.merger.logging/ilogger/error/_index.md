---
title: Error
second_title: GroupDocs.Merger for .NET API リファレンス
description: エラー ログ メッセージを書き込みます エラー ログ メッセージはアプリケーション フローの回復不能なイベントに関する情報を提供します
type: docs
weight: 10
url: /ja/net/groupdocs.merger.logging/ilogger/error/
---
## ILogger.Error method

エラー ログ メッセージを書き込みます。 エラー ログ メッセージは、アプリケーション フローの回復不能なイベントに関する情報を提供します。

```csharp
public void Error(string message, Exception exception)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| message | String | エラーメッセージ。 |
| exception | Exception | 例外。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*message*無効である。 |
| ArgumentNullException | スローされるタイミング*exception*無効である。 |

### 関連項目

* interface [ILogger](../../ilogger)
* 名前空間 [GroupDocs.Merger.Logging](../../ilogger)
* 組み立て [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->