---
title: "PageJoinOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для объединения документов."
type: docs
weight: 25
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Предоставляет параметры для объединения документов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Тип файла для объединения. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumbers | int[] | Номера страниц. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |
| pageNumbers | int[] | Номера страниц. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Создаёт новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### getType() {#getType--}
```
public final FileType getType()
```


Тип файла для объединения.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
