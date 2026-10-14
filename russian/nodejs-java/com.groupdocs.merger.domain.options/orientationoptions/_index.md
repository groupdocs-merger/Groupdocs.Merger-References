---
title: "OrientationOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для ориентации страницы."
type: docs
weight: 23
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Предоставляет параметры для ориентации страницы.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getMode()](#getMode--) | Получает режим ориентации страницы. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientationMode | int | Режим ориентации [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientationMode | int | Режим ориентации [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | Номера страниц. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientationMode | int | Режим ориентации [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Инициализирует новый экземпляр класса [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| orientationMode | int | Режим ориентации [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### getMode() {#getMode--}
```
public final int getMode()
```


Получает режим ориентации страницы.

**Returns:**
int
