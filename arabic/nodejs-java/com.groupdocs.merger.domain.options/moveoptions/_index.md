---
title: "MoveOptions"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يوفر خيارات لنقل صفحة المستند."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

يوفر خيارات لنقل صفحة المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | يقوم بتهيئة نسخة جديدة من الفئة [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | يحصل أو يعيّن رقم الصفحة للنقل. |
| [getNewPageNumber()](#getNewPageNumber--) | يحصل أو يعيّن رقم الصفحة الجديد. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


يقوم بتهيئة نسخة جديدة من الفئة [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNumberToMove | int | رقم الصفحة المراد نقلها. |
| newPageNumber | int | رقم الصفحة الجديد. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


يحصل أو يعيّن رقم الصفحة للنقل.

القيمة: رقم الصفحة للنقل.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


يحصل أو يعيّن رقم الصفحة الجديد.

القيمة: رقم الصفحة الجديد.

**Returns:**
int
