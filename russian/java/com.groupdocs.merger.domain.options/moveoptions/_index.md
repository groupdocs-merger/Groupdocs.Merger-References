---
title: "MoveOptions"
second_title: "Справочник API GroupDocs.Merger для Java"
description: "Предоставляет параметры для перемещения страниц документа."
type: docs
weight: 17
url: /ru/java/com.groupdocs.merger.domain.options/moveoptions/
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

Значение: номер страницы для перемещения.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Получает или задает новый номер страницы.

Значение: новый номер страницы.

**Returns:**
int
