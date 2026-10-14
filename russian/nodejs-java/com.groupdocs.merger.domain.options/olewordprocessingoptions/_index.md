---
title: "OleWordProcessingOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для импорта встроенного документа в Word processing через OLE."
type: docs
weight: 21
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Предоставляет параметры для импорта встроенного документа в Word processing через OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Инициализирует новый экземпляр класса [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Инициализирует новый экземпляр класса [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Инициализирует новый экземпляр класса [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getLeft()](#getLeft--) | Левая координата изображения объекта Ole. |
| [setLeft(int value)](#setLeft-int-) | Левая координата изображения объекта Ole. |
| [getTop()](#getTop--) | Верхняя координата изображения объекта Ole. |
| [setTop(int value)](#setTop-int-) | Верхняя координата изображения объекта Ole. |
| [getWidth()](#getWidth--) | Ширина изображения объекта Ole. |
| [setWidth(int value)](#setWidth-int-) | Ширина изображения объекта Ole. |
| [getHeight()](#getHeight--) | Высота изображения объекта Ole. |
| [setHeight(int value)](#setHeight-int-) | Высота изображения объекта Ole. |
| [getImageData()](#getImageData--) | Данные изображения объекта Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Инициализирует новый экземпляр класса [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectData | byte[] | Данные встроенного объекта. |
| imageData | byte[] | Данные изображения встроенного объекта. |
| расширение | java.lang.String | Расширение встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Инициализирует новый экземпляр класса [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |
| imageData | byte[] | Данные изображения встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Инициализирует новый экземпляр класса [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Левая координата изображения объекта Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Левая координата изображения объекта Ole.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Верхняя координата изображения объекта Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Верхняя координата изображения объекта Ole.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина изображения объекта Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина изображения объекта Ole.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота изображения объекта Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота изображения объекта Ole.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Данные изображения объекта Ole.

**Returns:**
byte[]
