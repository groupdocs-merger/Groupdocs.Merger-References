---
title: "ImportDocumentOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для импорта встроенного документа."
type: docs
weight: 14
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Предоставляет параметры для импорта встроенного документа.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]
 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]
 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]
 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]
 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Инициализирует новый экземпляр класса [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Инициализирует новый экземпляр класса [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectData()](#getObjectData--) | Данные встроенного объекта. |
| [getExtension()](#getExtension--) | Расширение встроенного объекта. |
| [getPageNumber()](#getPageNumber--) | Номер страницы для вставки встроенного объекта. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Получает данные изображения встроенного объекта. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Инициализирует новый экземпляр класса [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectData | byte[] | Данные встроенного объекта. |
| расширение | java.lang.String | Расширение встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Инициализирует новый экземпляр класса [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |
| pageNumber | int | Номер страницы для добавления встроенного объекта. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Данные встроенного объекта.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Расширение встроенного объекта.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Номер страницы для вставки встроенного объекта.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Получает данные изображения встроенного объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |

**Returns:**
byte[]
