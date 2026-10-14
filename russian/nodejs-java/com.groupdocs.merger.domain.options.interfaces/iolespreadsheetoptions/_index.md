---
title: "IOleSpreadsheetOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Интерфейс для параметров импорта встроенного документа в Spreadsheet через OLE."
type: docs
weight: 19
url: /ru/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Интерфейс для параметров импорта встроенного документа в Spreadsheet через OLE.
## Методы

| Метод | Описание |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | Индекс строки в верхнем левом углу. |
| [setRowIndex(int value)](#setRowIndex-int-) | Индекс строки в верхнем левом углу. |
| [getColumnIndex()](#getColumnIndex--) | Индекс столбца в верхнем левом углу. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Индекс столбца в верхнем левом углу. |
| [getImageData()](#getImageData--) | Данные изображения объекта Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Индекс строки в верхнем левом углу.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Индекс строки в верхнем левом углу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Индекс столбца в верхнем левом углу.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Индекс столбца в верхнем левом углу.

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
