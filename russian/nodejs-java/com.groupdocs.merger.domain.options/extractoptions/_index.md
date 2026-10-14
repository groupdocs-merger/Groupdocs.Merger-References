---
title: "ExtractOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для извлечения страниц документа."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/extractoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions)
```
public class ExtractOptions extends PageOptions implements IExtractOptions
```

Предоставляет параметры для извлечения страниц документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ExtractOptions()](#ExtractOptions--) | Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int[] pageNumbers)](#ExtractOptions-int---) | Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int startNumber, int endNumber)](#ExtractOptions-int-int-) | Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
| [ExtractOptions(int startNumber, int endNumber, int mode)](#ExtractOptions-int-int-int-) | Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions). |
### ExtractOptions() {#ExtractOptions--}
```
public ExtractOptions()
```


Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

### ExtractOptions(int[] pageNumbers) {#ExtractOptions-int---}
```
public ExtractOptions(int[] pageNumbers)
```


Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumbers | int[] | Номера страниц. |

### ExtractOptions(int startNumber, int endNumber) {#ExtractOptions-int-int-}
```
public ExtractOptions(int startNumber, int endNumber)
```


Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### ExtractOptions(int startNumber, int endNumber, int mode) {#ExtractOptions-int-int-int-}
```
public ExtractOptions(int startNumber, int endNumber, int mode)
```


Инициализирует новый экземпляр класса [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

