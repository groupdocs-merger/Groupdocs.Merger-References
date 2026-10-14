---
title: "ConsoleLogger"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "コンソールにログメッセージを書き込みます。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

コンソールにログメッセージを書き込みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | トレース メッセージをコンソールに書き込みます。 |
| [warning(String message)](#warning-java.lang.String-) | 警告メッセージをコンソールに書き込みます。 |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | エラーメッセージをコンソールに書き込みます。 |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


トレース メッセージをコンソールに書き込みます。トレース ログ メッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | トレース メッセージ。 |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


警告メッセージをコンソールに書き込みます。警告ログ メッセージは、アプリケーションのフローにおける予期しない回復可能なイベントに関する情報を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 警告メッセージ。 |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


エラーメッセージをコンソールに書き込みます。エラーログ メッセージは、アプリケーションのフローにおける回復不可能なイベントに関する情報を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | エラーメッセージ。 |
| 例外 | java.lang.Exception | 例外。 |

