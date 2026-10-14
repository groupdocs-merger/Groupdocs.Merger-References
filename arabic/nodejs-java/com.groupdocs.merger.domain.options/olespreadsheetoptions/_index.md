---
title: "OleSpreadsheetOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لاستيراد المستند المضمّن إلى جدول البيانات عبر OLE."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

يوفر خيارات لاستيراد المستند المضمّن إلى جدول البيانات عبر OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | ينشئ مثلاً جديداً من الفئة [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | ينشئ مثلاً جديداً من الفئة [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | ينشئ مثلاً جديداً من الفئة [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | فهرس الصف العلوي الأيسر. |
| [setRowIndex(int value)](#setRowIndex-int-) | فهرس الصف العلوي الأيسر. |
| [getColumnIndex()](#getColumnIndex--) | فهرس العمود العلوي الأيسر. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | فهرس العمود العلوي الأيسر. |
| [getWidth()](#getWidth--) | عرض صورة كائن Ole. |
| [setWidth(int value)](#setWidth-int-) | عرض صورة كائن Ole. |
| [getHeight()](#getHeight--) | ارتفاع صورة كائن Ole. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع صورة كائن Ole. |
| [getImageData()](#getImageData--) | بيانات صورة كائن Ole. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


ينشئ مثلاً جديداً من الفئة [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectData | byte[] | بيانات الكائن المدمج. |
| imageData | byte[] | بيانات الصورة للكائن المدمج. |
| امتداد | java.lang.String | امتداد الكائن المدمج. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


ينشئ مثلاً جديداً من الفئة [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمّن. |
| imageData | byte[] | بيانات الصورة للكائن المدمج. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


ينشئ مثلاً جديداً من الفئة [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمّن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


فهرس الصف العلوي الأيسر.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


فهرس الصف العلوي الأيسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


فهرس العمود العلوي الأيسر.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


فهرس العمود العلوي الأيسر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض صورة كائن Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض صورة كائن Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع صورة كائن Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع صورة كائن Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


بيانات صورة كائن Ole.

**Returns:**
byte[]
