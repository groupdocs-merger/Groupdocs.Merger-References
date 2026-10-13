---
title: "ConsoleLogger"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "콘솔에 로그 메시지를 기록합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

콘솔에 로그 메시지를 기록합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | 콘솔에 추적 메시지를 기록합니다. |
| [warning(String message)](#warning-java.lang.String-) | 콘솔에 경고 메시지를 기록합니다. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | 콘솔에 오류 메시지를 기록합니다. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


콘솔에 추적 메시지를 기록합니다. 추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 추적 메시지. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


콘솔에 경고 메시지를 기록합니다. 경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 경고 메시지. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


콘솔에 오류 메시지를 기록합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 메시지 | java.lang.String | 오류 메시지. |
| 예외 | java.lang.Exception | 예외. |

