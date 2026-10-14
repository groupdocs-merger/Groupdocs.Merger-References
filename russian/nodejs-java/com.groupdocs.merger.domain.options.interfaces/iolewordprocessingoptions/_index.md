---
title: "IOleWordProcessingOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров импорта встроенного документа в Word processing через OLE."
type: docs
weight: 20
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Интерфейс для параметров импорта встроенного документа в Word processing через OLE.
## Методы

| Метод | Описание |
| --- | --- |
| [getLeft()](#getLeft--) | Левая координата изображения объекта Ole. |
| [setLeft(int value)](#setLeft-int-) | Левая координата изображения объекта Ole. |
| [getTop()](#getTop--) | Верхняя координата изображения объекта Ole. |
| [setTop(int value)](#setTop-int-) | Верхняя координата изображения объекта Ole. |
| [getImageData()](#getImageData--) | Данные изображения объекта Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Левая координата изображения объекта Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Левая координата изображения объекта Ole.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Верхняя координата изображения объекта Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Верхняя координата изображения объекта Ole.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Данные изображения объекта Ole.

**Returns:**
byte[]
