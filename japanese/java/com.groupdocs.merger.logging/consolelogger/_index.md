---
title: "ConsoleLogger"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "コンソールにログメッセージを書き込みます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.merger.logging/consolelogger/
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
| [trace(String message)](#trace-java.lang.String-) | コンソールにトレースメッセージを書き込みます。 |
| [warning(String message)](#warning-java.lang.String-) | コンソールに警告メッセージを書き込みます。 |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | コンソールにエラーメッセージを書き込みます。 |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


コンソールにトレースメッセージを書き込みます。トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | トレースメッセージです。 |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


コンソールに警告メッセージを書き込みます。警告ログメッセージは、アプリケーションのフローにおける予期せぬ回復可能なイベントに関する情報を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 警告メッセージです。 |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


コンソールにエラーメッセージを書き込みます。エラーログメッセージは、アプリケーションのフローにおける回復不可能なイベントに関する情報を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | エラーメッセージ。 |
| 例外 | java.lang.Exception | 例外です。 |

