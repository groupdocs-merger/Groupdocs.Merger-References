---
title: "ConsoleLogger"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يكتب رسائل السجل إلى وحدة التحكم."
type: docs
weight: 10
url: /ar/java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

يكتب رسائل السجل إلى وحدة التحكم.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | يكتب رسالة تتبع إلى وحدة التحكم. |
| [warning(String message)](#warning-java.lang.String-) | يكتب رسالة تحذير إلى وحدة التحكم. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | يكتب رسالة خطأ إلى وحدة التحكم. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


يكتب رسالة تتبع إلى وحدة التحكم. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة التتبع. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


يكتب رسالة تحذير إلى وحدة التحكم. رسائل سجل التحذير توفر معلومات حول حدث غير متوقع وقابل للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة التحذير. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


يكتب رسالة الخطأ إلى وحدة التحكم. رسائل سجل الأخطاء توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة الخطأ. |
| استثناء | java.lang.Exception | الاستثناء. |

