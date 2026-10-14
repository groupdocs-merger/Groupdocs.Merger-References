---
title: "PageInfo"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Определяет свойства описания страницы."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Определяет свойства описания страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Инициализирует новый экземпляр класса [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Инициализирует новый экземпляр класса [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Методы

| Метод | Описание |
| --- | --- |
| [getDocument()](#getDocument--) | Получает информацию о документе. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Получает информацию о документе. |
| [getNumber()](#getNumber--) | Получает номер страницы. |
| [getVisible()](#getVisible--) | Указывает, видима ли страница или нет. |
| [getWidth()](#getWidth--) | Получает ширину страницы в пикселях при преобразовании в изображение. |
| [getHeight()](#getHeight--) | Получает высоту страницы в пикселях при преобразовании в изображение. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Инициализирует новый экземпляр класса [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| number | int | Номер страницы. |
| visible | boolean | Индикатор видимости страницы. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Инициализирует новый экземпляр класса [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| number | int | Номер страницы. |
| visible | boolean | Индикатор видимости страницы. |
| width | int | Ширина страницы в пикселях при просмотре в формате JPG или PNG. |
| height | int | Высота страницы в пикселях при просмотре в формате JPG или PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Получает информацию о документе.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Получает информацию о документе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Получает номер страницы.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Указывает, видима ли страница или нет.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Получает ширину страницы в пикселях при преобразовании в изображение.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Получает высоту страницы в пикселях при преобразовании в изображение.

**Returns:**
int
