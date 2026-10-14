---
title: "IOleDiagramOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров импорта встроенного документа в Diagram через OLE."
type: docs
weight: 17
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Интерфейс для параметров импорта встроенного документа в Diagram через OLE.
## Методы

| Метод | Описание |
| --- | --- |
| [getX()](#getX--) | Координата X привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [setX(int value)](#setX-int-) | Координата X привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [getY()](#getY--) | Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [setY(int value)](#setY-int-) | Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [getImageData()](#getImageData--) | Данные изображения встроенного объекта. |
### getX() {#getX--}
```
public abstract int getX()
```


Координата X привязки формы встроенного объекта (центр вращения) относительно страницы.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


Координата X привязки формы встроенного объекта (центр вращения) относительно страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Данные изображения встроенного объекта.

**Returns:**
byte[]
