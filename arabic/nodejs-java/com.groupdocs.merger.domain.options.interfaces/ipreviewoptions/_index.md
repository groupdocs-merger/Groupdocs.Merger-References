---
title: "IPreviewOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "واجهة لخيارات المعاينة."
type: docs
weight: 28
url: /ar/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

واجهة لخيارات المعاينة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | عرض المعاينة. |
| [setWidth(int value)](#setWidth-int-) | عرض المعاينة. |
| [getHeight()](#getHeight--) | ارتفاع المعاينة. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع المعاينة. |
| [getResolution()](#getResolution--) | دقة الصورة. |
| [setResolution(int value)](#setResolution-int-) | دقة الصورة. |
| [getMode()](#getMode--) | يحصل على وضع المعاينة. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | يتحقق من صحة خيارات التقسيم. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | يحصل على المسار الكامل للملف للمستند المعاين حسب رقم الصفحة مع الامتداد المحدد. |
| [getPageStreamFactory()](#getPageStreamFactory--) | المندوب الذي يحدد الطريقة لإنشاء تدفق معاينة صفحة الإخراج. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


عرض المعاينة.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


عرض المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


ارتفاع المعاينة.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


ارتفاع المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


دقة الصورة.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


دقة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


يحصل على وضع المعاينة.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


يتحقق من صحة خيارات التقسيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف لفئة [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


يحصل على المسار الكامل للملف للمستند المعاين حسب رقم الصفحة مع الامتداد المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumber | int | رقم صفحة المعاينة. |
| امتداد | java.lang.String | امتداد الملف. |

**Returns:**
java.lang.String - المسار الكامل للملف.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


المندوب الذي يحدد الطريقة لإنشاء تدفق معاينة صفحة الإخراج.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
