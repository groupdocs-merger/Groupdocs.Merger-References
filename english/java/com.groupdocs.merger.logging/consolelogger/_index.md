---
title: ConsoleLogger
second_title: GroupDocs.Merger for Java API Reference
description:  Writes log messages to the console.
type: docs
weight: 10
url: /java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Writes log messages to the console.
## Constructors

| Constructor | Description |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Methods

| Method | Description |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Writes trace message to the console. |
| [warning(String message)](#warning-java.lang.String-) | Writes warning message to the console. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Writes error message to the console. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Writes trace message to the console. Trace log messages provides generally useful information about application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The trace message. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Writes warning message to the console. Warning log messages provides information about unexpected and recoverable event in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The warning message. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Writes error message to the console. Error log messages provides information about unrecoverable events in application flow.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | The error message. |
| exception | java.lang.Exception | The exception. |

