---
title: "ISplitOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров разбиения."
type: docs
weight: 33
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Интерфейс для параметров разбиения.
## Методы

| Метод | Описание |
| --- | --- |
| [getMode()](#getMode--) | Получает режим разбиения страниц. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Проверяет параметры разбиения. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Получает полный путь к файлу разделённого документа по индексу с заданным расширением. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Делегат, определяющий метод для создания выходного разделённого потока. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Получает режим разбиения страниц.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Проверяет параметры разбиения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла класса [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


Получает полный путь к файлу разделённого документа по индексу с заданным расширением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс разделённого документа. |
| расширение | java.lang.String | Расширение файла. |

**Returns:**
java.lang.String - Полный путь к файлу.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


Делегат, определяющий метод для создания выходного разделённого потока.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
