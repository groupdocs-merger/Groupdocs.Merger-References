---
title: "RotateOptions"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "يوفر خيارات لتدوير الصفحة."
type: docs
weight: 35
url: /ar/java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

يوفر خيارات لتدوير الصفحة.
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMode()](#getMode--) | يحصل على وضعية الدوران (90، 180 أو 270 درجة). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | أرقام الصفحات. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


ينشئ مثلاً جديداً من الفئة [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rotateMode | int | وضع الدوران للـ Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | رقم الصفحة البداية. |
| endNumber | int | رقم الصفحة النهاية. |
| الوضع | int | وضع النطاق. |

### getMode() {#getMode--}
```
public final int getMode()
```


يحصل على وضعية الدوران (90، 180 أو 270 درجة).

**Returns:**
int
