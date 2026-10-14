---
title: "ConsoleLogger"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "将日志消息写入控制台。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

将日志消息写入控制台。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | 将跟踪消息写入控制台。 |
| [warning(String message)](#warning-java.lang.String-) | 将警告消息写入控制台。 |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | 将错误消息写入控制台。 |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


将跟踪消息写入控制台。跟踪日志消息提供有关应用程序流程的一般有用信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 跟踪消息。 |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


将警告消息写入控制台。警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 警告消息。 |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


将错误消息写入控制台。错误日志消息提供有关应用程序流程中不可恢复事件的信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 错误消息。 |
| 异常 | java.lang.Exception | 异常。 |

