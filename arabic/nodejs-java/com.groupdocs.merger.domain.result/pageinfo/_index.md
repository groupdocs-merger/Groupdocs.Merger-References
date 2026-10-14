---
title: "PageInfo"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يحدد خصائص وصف الصفحة."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

يحدد خصائص وصف الصفحة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | ينشئ مثيلاً جديدًا من الفئة [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | ينشئ مثيلاً جديدًا من الفئة [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDocument()](#getDocument--) | يحصل على معلومات المستند. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | يحصل على معلومات المستند. |
| [getNumber()](#getNumber--) | يحصل على رقم الصفحة. |
| [getVisible()](#getVisible--) | يشير إلى ما إذا كانت الصفحة مرئية أم لا. |
| [getWidth()](#getWidth--) | يحصل على عرض الصفحة بالبكسل عند تحويلها إلى صورة. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصفحة بالبكسل عند تحويلها إلى صورة. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


ينشئ مثيلاً جديدًا من الفئة [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| number | int | رقم الصفحة. |
| visible | boolean | مؤشر رؤية الصفحة. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


ينشئ مثيلاً جديدًا من الفئة [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| number | int | رقم الصفحة. |
| visible | boolean | مؤشر رؤية الصفحة. |
| width | int | عرض الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |
| height | int | ارتفاع الصفحة بالبكسل عند عرضها كملف JPG أو PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


يحصل على معلومات المستند.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


يحصل على معلومات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


يحصل على رقم الصفحة.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


يشير إلى ما إذا كانت الصفحة مرئية أم لا.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض الصفحة بالبكسل عند تحويلها إلى صورة.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع الصفحة بالبكسل عند تحويلها إلى صورة.

**Returns:**
int
