---
title: "PreviewOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يمثل خيارات معاينة المستند."
type: docs
weight: 29
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

يمثل خيارات معاينة المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | عرض المعاينة. |
| [setWidth(int value)](#setWidth-int-) | عرض المعاينة. |
| [getHeight()](#getHeight--) | ارتفاع المعاينة. |
| [setHeight(int value)](#setHeight-int-) | ارتفاع المعاينة. |
| [getResolution()](#getResolution--) | دقة الصورة. |
| [setResolution(int value)](#setResolution-int-) | دقة الصورة. |
| [getMode()](#getMode--) | وضع المعاينة. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | يتحقق من صحة خيارات المعاينة. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | يحصل على المسار الكامل للملف للمستند المعاين حسب رقم الصفحة مع الامتداد المحدد. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory لإنشاء أو تحرير تدفق معاينة صفحة الإخراج. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| previewMode | int | وضع المعاينة لـ Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| previewMode | int | وضع المعاينة لـ Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| pageNumbers | int[] | أرقام الصفحات. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| previewMode | int | وضع المعاينة لـ Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


ينشئ مثيلاً جديدًا من الفئة [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | الطريقة التي تنشئ التدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| previewMode | int | وضع المعاينة لـ Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | int | وضع النطاق. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


عرض المعاينة.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


عرض المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


ارتفاع المعاينة.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


ارتفاع المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


دقة الصورة.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


دقة الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


وضع المعاينة.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


يتحقق من صحة خيارات المعاينة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory لإنشاء أو تحرير تدفق معاينة صفحة الإخراج.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
