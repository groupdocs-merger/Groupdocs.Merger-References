---
title: "IOleSpreadsheetOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "واجهة لخيارات استيراد المستند المضمّن إلى جدول البيانات عبر OLE."
type: docs
weight: 19
url: /ar/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

واجهة لخيارات استيراد المستند المضمّن إلى جدول البيانات عبر OLE.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | فهرس الصف العلوي الأيسر. |
| [setRowIndex(int value)](#setRowIndex-int-) | فهرس الصف العلوي الأيسر. |
| [getColumnIndex()](#getColumnIndex--) | فهرس العمود العلوي الأيسر. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | فهرس العمود العلوي الأيسر. |
| [getImageData()](#getImageData--) | بيانات صورة كائن Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


فهرس الصف العلوي الأيسر.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


فهرس الصف العلوي الأيسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


فهرس العمود العلوي الأيسر.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


فهرس العمود العلوي الأيسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


بيانات صورة كائن Ole.

**Returns:**
byte[]
