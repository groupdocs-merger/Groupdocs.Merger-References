---
title: "OleDiagramOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для импорта встроенного документа в Diagram через OLE."
type: docs
weight: 18
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Предоставляет параметры для импорта встроенного документа в Diagram через OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Инициализирует новый экземпляр класса [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Инициализирует новый экземпляр класса [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Инициализирует новый экземпляр класса [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getX()](#getX--) | Координата X привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [setX(int value)](#setX-int-) | Координата X привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [getY()](#getY--) | Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [setY(int value)](#setY-int-) | Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы. |
| [getWidth()](#getWidth--) | Ширина формы встроенного объекта в дюймах. |
| [setWidth(int value)](#setWidth-int-) | Ширина формы встроенного объекта в дюймах. |
| [getHeight()](#getHeight--) | Высота формы встроенного объекта в дюймах. |
| [setHeight(int value)](#setHeight-int-) | Высота формы встроенного объекта в дюймах. |
| [getImageData()](#getImageData--) | Данные изображения встроенного объекта. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Инициализирует новый экземпляр класса [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectData | byte[] | Данные встроенного объекта. |
| imageData | byte[] | Данные изображения встроенного объекта. |
| расширение | java.lang.String | Расширение встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Инициализирует новый экземпляр класса [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |
| imageData | byte[] | Данные изображения встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Инициализирует новый экземпляр класса [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### getX() {#getX--}
```
public final int getX()
```


Координата X привязки формы встроенного объекта (центр вращения) относительно страницы.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Координата X привязки формы встроенного объекта (центр вращения) относительно страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Координата Y привязки формы встроенного объекта (центр вращения) относительно страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина формы встроенного объекта в дюймах.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина формы встроенного объекта в дюймах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота формы встроенного объекта в дюймах.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота формы встроенного объекта в дюймах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Данные изображения встроенного объекта.

**Returns:**
byte[]
