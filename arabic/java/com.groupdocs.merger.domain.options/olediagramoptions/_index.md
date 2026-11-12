---
title: "OleDiagramOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر خيارات لاستيراد المستند المضمّن إلى المخطط عبر OLE."
type: docs
weight: 18
url: /ar/java/com.groupdocs.merger.domain.options/olediagramoptions/
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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | يُنشئ نسخة جديدة من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | يُنشئ نسخة جديدة من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | يُنشئ نسخة جديدة من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | الإحداثي X لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة. |
| [setX(int value)](#setX-int-) | الإحداثي X لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة. |
| [getY()](#getY--) | الإحداثي Y لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة. |
| [setY(int value)](#setY-int-) | الإحداثي Y لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة. |
| [getWidth()](#getWidth--) | عرض شكل الكائن المضمن بالبوصة. |
| [setWidth(int value)](#setWidth-int-) | عرض شكل الكائن المضمن بالبوصة. |
| [getHeight()](#getHeight--) | ارتفاع شكل الكائن المضمن بالبوصة. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع شكل الكائن المضمن بالبوصة. |
| [getImageData()](#getImageData--) | بيانات الصورة للكائن المضمن. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


يُنشئ نسخة جديدة من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectData | byte[] | بيانات الكائن المضمن. |
| imageData | byte[] | بيانات الصورة للكائن المضمن. |
| امتداد | java.lang.String | امتداد الكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


يُنشئ نسخة جديدة من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمن. |
| imageData | byte[] | بيانات الصورة للكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


يُنشئ نسخة جديدة من الفئة [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمن. |

### getX() {#getX--}
```
public final int getX()
```


الإحداثي X لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


الإحداثي X لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getY() {#getY--}
```
public final int getY()
```


الإحداثي Y لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


الإحداثي Y لدبوس شكل الكائن المضمن (مركز الدوران) بالنسبة للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض شكل الكائن المضمن بالبوصة.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض شكل الكائن المضمن بالبوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع شكل الكائن المضمن بالبوصة.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع شكل الكائن المضمن بالبوصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


بيانات الصورة للكائن المضمن.

**Returns:**
byte[]
