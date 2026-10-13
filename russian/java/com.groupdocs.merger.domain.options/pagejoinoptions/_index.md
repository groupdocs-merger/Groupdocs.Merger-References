---
title: "PageJoinOptions"
second_title: "Справочник API GroupDocs.Merger для Java"
description: "Предоставляет параметры для объединения документов."
type: docs
weight: 25
url: /ru/java/com.groupdocs.merger.domain.options/pagejoinoptions/
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
| [PageJoinOptions()](#PageJoinOptions--) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Тип файла для объединения. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumbers | int[] | Номера страниц. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| режим | int | Режим диапазона. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |
| pageNumbers | int[] | Номера страниц. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

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


Инициализирует новый экземпляр класса [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла для объединения. |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| режим | int | Режим диапазона. |

### getType() {#getType--}
```
public final FileType getType()
```


Тип файла для объединения.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
