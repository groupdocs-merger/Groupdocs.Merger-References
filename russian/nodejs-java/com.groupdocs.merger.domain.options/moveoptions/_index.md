---
title: "MoveOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для перемещения страниц документа."
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Предоставляет параметры для перемещения страниц документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Инициализирует новый экземпляр класса [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Получает или задает номер страницы для перемещения. |
| [getNewPageNumber()](#getNewPageNumber--) | Получает или задает новый номер страницы. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Инициализирует новый экземпляр класса [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumberToMove | int | Номер страницы для перемещения. |
| newPageNumber | int | Новый номер страницы. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Получает или задает номер страницы для перемещения.

Значение: Номер страницы для перемещения.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Получает или задает новый номер страницы.

Значение: Новый номер страницы.

**Returns:**
int
