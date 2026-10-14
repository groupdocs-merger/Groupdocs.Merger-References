---
title: "GroupDocsMergerException"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Представляет ошибки, возникающие во время обработки документа."
type: docs
weight: 12
url: /ru/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

Представляет ошибки, возникающие во время обработки документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | Инициализирует новый экземпляр класса [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | Инициализирует новый экземпляр класса [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception). |
## Методы

| Метод | Описание |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | Получить исключение GroupDocs Merger из входного исключения. |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


Инициализирует новый экземпляр класса [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение, описывающее ошибку. |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


Инициализирует новый экземпляр класса [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| сообщение | java.lang.String | Сообщение, описывающее ошибку. |
| innerException | java.lang.Exception | Внутреннее исключение ошибки. |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


Получить исключение GroupDocs Merger из входного исключения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| исключение | java.lang.Exception | Входное исключение. |

**Returns:**
java.lang.Exception -
