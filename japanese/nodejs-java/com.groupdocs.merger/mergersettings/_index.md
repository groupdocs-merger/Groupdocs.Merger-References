---
title: "MergerSettings"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "動作をカスタマイズするための設定を定義します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

カスタマイズされた[Merger](../../com.groupdocs.merger/merger)の動作の設定を定義します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | 新しい[MergerSettings](../../com.groupdocs.merger/mergersettings)クラスのインスタンスを初期化します。 |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | 新しい[MergerSettings](../../com.groupdocs.merger/mergersettings)クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLogger()](#getLogger--) | ドキュメント処理ワークフローの追跡に使用されるロガー実装です。 |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | ドキュメント処理ワークフローの追跡に使用されるロガー実装です。 |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


新しい[MergerSettings](../../com.groupdocs.merger/mergersettings)クラスのインスタンスを初期化します。

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


新しい[MergerSettings](../../com.groupdocs.merger/mergersettings)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | ロガー実装です。 |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


ドキュメント処理ワークフローの追跡に使用されるロガー実装です。

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


ドキュメント処理ワークフローの追跡に使用されるロガー実装です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

