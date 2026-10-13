---
title: "OleWordProcessingOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر خيارات لاستيراد المستند المضمّن إلى معالجة النصوص عبر OLE."
type: docs
weight: 21
url: /ar/java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

يوفر خيارات لاستيراد المستند المضمّن إلى معالجة النصوص عبر OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | يُهيئ مثلاً جديداً من الفئة [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | يُهيئ مثلاً جديداً من الفئة [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | يُهيئ مثلاً جديداً من الفئة [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLeft()](#getLeft--) | الإحداثي الأيسر لصورة كائن Ole. |
| [setLeft(int value)](#setLeft-int-) | الإحداثي الأيسر لصورة كائن Ole. |
| [getTop()](#getTop--) | الإحداثي العلوي لصورة كائن Ole. |
| [setTop(int value)](#setTop-int-) | الإحداثي العلوي لصورة كائن Ole. |
| [getWidth()](#getWidth--) | عرض صورة كائن Ole. |
| [setWidth(int value)](#setWidth-int-) | عرض صورة كائن Ole. |
| [getHeight()](#getHeight--) | ارتفاع صورة كائن Ole. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع صورة كائن Ole. |
| [getImageData()](#getImageData--) | بيانات صورة كائن Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


يُهيئ مثلاً جديداً من الفئة [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectData | byte[] | بيانات الكائن المضمن. |
| imageData | byte[] | بيانات الصورة للكائن المضمن. |
| امتداد | java.lang.String | امتداد الكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


يُهيئ مثلاً جديداً من الفئة [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمن. |
| imageData | byte[] | بيانات الصورة للكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


يُهيئ مثلاً جديداً من الفئة [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


الإحداثي الأيسر لصورة كائن Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


الإحداثي الأيسر لصورة كائن Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


الإحداثي العلوي لصورة كائن Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


الإحداثي العلوي لصورة كائن Ole.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

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
| القيمة | int |  |

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
| القيمة | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


بيانات صورة كائن Ole.

**Returns:**
byte[]
