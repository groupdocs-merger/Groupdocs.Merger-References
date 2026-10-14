---
title: "OleDiagramOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لاستيراد المستند المضمّن إلى المخطط عبر OLE."
type: docs
weight: 18
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

يوفر خيارات لاستيراد المستند المضمّن إلى المخطط عبر OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | يُنشئ مثيلاً جديدًا من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | يُنشئ مثيلاً جديدًا من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | يُنشئ مثيلاً جديدًا من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [setX(int value)](#setX-int-) | الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [getY()](#getY--) | الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [setY(int value)](#setY-int-) | الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [getWidth()](#getWidth--) | عرض الشكل المدمج بوحدة البوصة. |
| [setWidth(int value)](#setWidth-int-) | عرض الشكل المدمج بوحدة البوصة. |
| [getHeight()](#getHeight--) | ارتفاع الشكل المدمج بوحدة البوصة. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع الشكل المدمج بوحدة البوصة. |
| [getImageData()](#getImageData--) | بيانات الصورة للكائن المدمج. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


يُنشئ مثيلاً جديدًا من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectData | byte[] | بيانات الكائن المدمج. |
| imageData | byte[] | بيانات الصورة للكائن المدمج. |
| امتداد | java.lang.String | امتداد الكائن المدمج. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


يُنشئ مثيلاً جديدًا من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمّن. |
| imageData | byte[] | بيانات الصورة للكائن المدمج. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


يُنشئ مثيلاً جديدًا من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمّن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### getX() {#getX--}
```
public final int getX()
```


الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض الشكل المدمج بوحدة البوصة.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض الشكل المدمج بوحدة البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع الشكل المدمج بوحدة البوصة.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع الشكل المدمج بوحدة البوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


بيانات الصورة للكائن المدمج.

**Returns:**
byte[]
