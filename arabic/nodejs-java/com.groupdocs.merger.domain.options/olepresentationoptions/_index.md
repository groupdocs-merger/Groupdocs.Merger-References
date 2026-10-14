---
title: "OlePresentationOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لاستيراد المستند المضمّن إلى العرض التقديمي عبر OLE."
type: docs
weight: 19
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

يوفر خيارات لاستيراد المستند المضمّن إلى العرض التقديمي عبر OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | يقوم بإنشاء نسخة جديدة من الفئة [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | يقوم بإنشاء نسخة جديدة من الفئة [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | الإحداثي X لإطار الكائن المضمن. |
| [setX(int value)](#setX-int-) | الإحداثي X لإطار الكائن المضمن. |
| [getY()](#getY--) | الإحداثي Y لإطار الكائن المضمن. |
| [setY(int value)](#setY-int-) | الإحداثي Y لإطار الكائن المضمن. |
| [getWidth()](#getWidth--) | عرض إطار الكائن المدمج. |
| [setWidth(int value)](#setWidth-int-) | عرض إطار الكائن المدمج. |
| [getHeight()](#getHeight--) | ارتفاع إطار الكائن المدمج. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع إطار الكائن المدمج. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


يقوم بإنشاء نسخة جديدة من الفئة [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectData | byte[] | بيانات الكائن المدمج. |
| امتداد | java.lang.String | امتداد الكائن المدمج. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


يقوم بإنشاء نسخة جديدة من الفئة [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار ملف الكائن المضمّن. |
| pageNumber | int | رقم الصفحة لإضافة الكائن المضمّن. |

### getX() {#getX--}
```
public final int getX()
```


الإحداثي X لإطار الكائن المضمن.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


الإحداثي X لإطار الكائن المضمن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


الإحداثي Y لإطار الكائن المضمن.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


الإحداثي Y لإطار الكائن المضمن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض إطار الكائن المدمج.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض إطار الكائن المدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع إطار الكائن المدمج.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع إطار الكائن المدمج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

