---
title: "RotateOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لتدوير الصفحة."
type: docs
weight: 33
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

يوفر خيارات لتدوير الصفحة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMode()](#getMode--) | يحصل على وضع الدوران (90 أو 180 أو 270 درجة). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| pageNumbers | int[] | أرقام الصفحات. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


يقوم بتهيئة نسخة جديدة من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| mode | int | وضع النطاق. |

### getMode() {#getMode--}
```
public final int getMode()
```


يحصل على وضع الدوران (90 أو 180 أو 270 درجة).

**Returns:**
int
