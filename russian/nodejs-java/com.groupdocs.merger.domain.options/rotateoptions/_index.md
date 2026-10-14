---
title: "RotateOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для вращения страниц."
type: docs
weight: 33
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Предоставляет параметры для вращения страниц.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getMode()](#getMode--) | Получает режим вращения (90, 180 или 270 градусов). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateMode | int | Режим вращения Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateMode | int | Режим вращения Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Номера страниц. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateMode | int | Режим вращения Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Инициализирует новый экземпляр класса [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rotateMode | int | Режим вращения Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### getMode() {#getMode--}
```
public final int getMode()
```


Получает режим вращения (90, 180 или 270 градусов).

**Returns:**
int
