---
title: "IOleSpreadsheetOptions"
second_title: "Справочник API GroupDocs.Merger для Java"
description: "Интерфейс для параметров импорта встроенного документа в Spreadsheet через OLE."
type: docs
weight: 19
url: /ru/java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
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
| [getRowIndex()](#getRowIndex--) | Индекс верхней левой строки. |
| [setRowIndex(int value)](#setRowIndex-int-) | Индекс верхней левой строки. |
| [getColumnIndex()](#getColumnIndex--) | Индекс верхнего левого столбца. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | Индекс верхнего левого столбца. |
| [getImageData()](#getImageData--) | Данные изображения объекта Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


Индекс верхней левой строки.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


Индекс верхней левой строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


Индекс верхнего левого столбца.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


Индекс верхнего левого столбца.

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
