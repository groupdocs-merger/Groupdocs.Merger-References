---
title: "OlePresentationOptions"
second_title: "Справочник API GroupDocs.Merger для Java"
description: "Предоставляет параметры для импорта встроенного документа в Presentation через OLE."
type: docs
weight: 19
url: /ru/java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Предоставляет параметры для импорта встроенного документа в Presentation через OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Инициализирует новый экземпляр класса [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Инициализирует новый экземпляр класса [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getX()](#getX--) | Координата X встраиваемого кадра объекта. |
| [setX(int value)](#setX-int-) | Координата X встраиваемого кадра объекта. |
| [getY()](#getY--) | Координата Y встраиваемого кадра объекта. |
| [setY(int value)](#setY-int-) | Координата Y встраиваемого кадра объекта. |
| [getWidth()](#getWidth--) | Ширина кадра встроенного объекта. |
| [setWidth(int value)](#setWidth-int-) | Ширина кадра встроенного объекта. |
| [getHeight()](#getHeight--) | Высота кадра встроенного объекта. |
| [setHeight(int value)](#setHeight-int-) | Высота кадра встроенного объекта. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Инициализирует новый экземпляр класса [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectData | byte[] | Данные встроенного объекта. |
| расширение | java.lang.String | Расширение встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Инициализирует новый экземпляр класса [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### getX() {#getX--}
```
public final int getX()
```


Координата X встраиваемого кадра объекта.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Координата X встраиваемого кадра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Координата Y встраиваемого кадра объекта.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Координата Y встраиваемого кадра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина кадра встроенного объекта.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина кадра встроенного объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота кадра встроенного объекта.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота кадра встроенного объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

