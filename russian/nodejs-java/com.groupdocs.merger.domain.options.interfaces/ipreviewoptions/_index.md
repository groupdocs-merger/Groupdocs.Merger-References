---
title: "IPreviewOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров предварительного просмотра."
type: docs
weight: 28
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Интерфейс для параметров предварительного просмотра.
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Ширина предварительного просмотра. |
| [setWidth(int value)](#setWidth-int-) | Ширина предварительного просмотра. |
| [getHeight()](#getHeight--) | Высота предварительного просмотра. |
| [setHeight(int value)](#setHeight-int-) | Высота предварительного просмотра. |
| [getResolution()](#getResolution--) | Разрешение изображения. |
| [setResolution(int value)](#setResolution-int-) | Разрешение изображения. |
| [getMode()](#getMode--) | Получает режим предварительного просмотра. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Проверяет параметры разбиения. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Получает полный путь к файлу предварительно просмотренного документа по номеру страницы с указанным расширением. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Делегат, определяющий метод создания потока предварительного просмотра выходной страницы. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Ширина предварительного просмотра.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Ширина предварительного просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Высота предварительного просмотра.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Высота предварительного просмотра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Разрешение изображения.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Разрешение изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Получает режим предварительного просмотра.

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

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
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
public abstract PageStreamFactory getPageStreamFactory()
```


Делегат, определяющий метод создания потока предварительного просмотра выходной страницы.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
