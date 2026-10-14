---
title: "OrientationOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لاتجاه الصفحة."
type: docs
weight: 23
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

يوفر خيارات لاتجاه الصفحة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMode()](#getMode--) | يحصل على وضع توجيه الصفحة. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| orientationMode | int | وضعية الاتجاه لـ [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| orientationMode | int | وضعية الاتجاه لـ [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | أرقام الصفحات. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| orientationMode | int | وضعية الاتجاه لـ [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


يقوم بإنشاء نسخة جديدة من الفئة [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| orientationMode | int | وضعية الاتجاه لـ [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | int | وضع النطاق. |

### getMode() {#getMode--}
```
public final int getMode()
```


يحصل على وضع توجيه الصفحة.

**Returns:**
int
