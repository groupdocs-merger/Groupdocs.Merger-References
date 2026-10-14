---
title: "IOleDiagramOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "واجهة لخيارات استيراد المستند المضمّن إلى المخطط عبر OLE."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

واجهة لخيارات استيراد المستند المضمّن إلى المخطط عبر OLE.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getX()](#getX--) | الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [setX(int value)](#setX-int-) | الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [getY()](#getY--) | الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [setY(int value)](#setY-int-) | الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة. |
| [getImageData()](#getImageData--) | بيانات الصورة للكائن المدمج. |
### getX() {#getX--}
```
public abstract int getX()
```


الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


الإحداثي X لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


الإحداثي Y لدبوس شكل الكائن المدمج (مركز الدوران) بالنسبة للصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


بيانات الصورة للكائن المدمج.

**Returns:**
byte[]
