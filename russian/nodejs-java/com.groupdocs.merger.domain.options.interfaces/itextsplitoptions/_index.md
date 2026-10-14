---
title: "ITextSplitOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров разбиения текста."
type: docs
weight: 35
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Интерфейс для параметров разбиения текста.
## Методы

| Метод | Описание |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Номера строк для разбиения текста. |
| [getMode()](#getMode--) | Режим разбиения текста. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Проверяет параметры разбиения. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Получает полный путь к файлу разделённого документа по индексу с заданным расширением. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Делегат, определяющий метод для создания выходного разделённого потока. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Номера строк для разбиения текста.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Режим разбиения текста.

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
