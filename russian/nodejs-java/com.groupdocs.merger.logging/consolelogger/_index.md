---
title: "ConsoleLogger"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Записывает сообщения журнала в консоль."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.merger.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.logging.ILogger](../../com.groupdocs.merger.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

Записывает сообщения журнала в консоль.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [trace(String message)](#trace-java.lang.String-) | Записывает трассировочное сообщение в консоль. |
| [warning(String message)](#warning-java.lang.String-) | Записывает предупреждающее сообщение в консоль. |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | Записывает сообщение об ошибке в консоль. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


Записывает трассировочное сообщение в консоль. Трассировочные сообщения журнала предоставляют общую полезную информацию о потоке выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Трассировочное сообщение. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


Записывает предупреждающее сообщение в консоль. Предупреждающие сообщения журнала предоставляют информацию о неожиданных и восстанавливаемых событиях в потоке выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Предупреждающее сообщение. |

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


Записывает сообщение об ошибке в консоль. Сообщения об ошибках журнала предоставляют информацию о необратимых событиях в потоке выполнения приложения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение об ошибке. |
| исключение | java.lang.Exception | Исключение. |

