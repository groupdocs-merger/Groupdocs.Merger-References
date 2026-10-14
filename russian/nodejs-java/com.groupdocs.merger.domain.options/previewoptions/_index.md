---
title: "PreviewOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Представляет параметры предварительного просмотра документа."
type: docs
weight: 29
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Представляет параметры предварительного просмотра документа.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Ширина предварительного просмотра. |
| [setWidth(int value)](#setWidth-int-) | Ширина предварительного просмотра. |
| [getHeight()](#getHeight--) | Высота предварительного просмотра. |
| [setHeight(int value)](#setHeight-int-) | Высота предварительного просмотра. |
| [getResolution()](#getResolution--) | Разрешение изображения. |
| [setResolution(int value)](#setResolution-int-) | Разрешение изображения. |
| [getMode()](#getMode--) | Режим предварительного просмотра. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Проверяет параметры предварительного просмотра. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Получает полный путь к файлу предварительно просмотренного документа по номеру страницы с указанным расширением. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory для создания или освобождения потока предварительного просмотра выходной страницы. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Метод, который создает поток, используемый для записи данных выходной страницы. |
| previewMode | int | Режим предварительного просмотра Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Метод, который создает поток, используемый для записи данных выходной страницы. |
| previewMode | int | Режим предварительного просмотра Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Номера страниц. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Метод, который создает поток, используемый для записи данных выходной страницы. |
| previewMode | int | Режим предварительного просмотра Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Инициализирует новый экземпляр класса [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Метод, который создает поток, используемый для записи данных выходной страницы. |
| previewMode | int | Режим предварительного просмотра Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Номер начальной страницы. |
| endNumber | int | Номер конечной страницы. |
| mode | int | Режим диапазона. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина предварительного просмотра.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина предварительного просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота предварительного просмотра.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота предварительного просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Разрешение изображения.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Разрешение изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Режим предварительного просмотра.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Проверяет параметры предварительного просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип файла. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Получает полный путь к файлу предварительно просмотренного документа по номеру страницы с указанным расширением.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int | Номер страницы предварительного просмотра. |
| расширение | java.lang.String | Расширение файла. |

**Returns:**
java.lang.String - Полный путь к файлу.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory для создания или освобождения потока предварительного просмотра выходной страницы.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
