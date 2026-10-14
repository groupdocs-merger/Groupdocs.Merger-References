---
title: "DocumentInfo"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "يحدد خصائص وصف المستند."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

يحدد خصائص وصف المستند.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | ينشئ نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | ينشئ نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | ينشئ نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getIndex()](#getIndex--) | فهرس المستند. |
| [getStream()](#getStream--) | تيار المستند. |
| [getPassword()](#getPassword--) | كلمة مرور المستند. |
| [getType()](#getType--) | يحصل على نوع الملف. |
| [getPages()](#getPages--) | يحدد مجموعة صفحات المستند. |
| [getPageCount()](#getPageCount--) | عدد صفحات المستند. |
| [getSize()](#getSize--) | حجم المستند بالبايت |
| [toString()](#toString--) | يعيد سلسلة تمثل الكائن الحالي. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


ينشئ نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int |  |
| دفق | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف. |
| كلمة المرور | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


ينشئ نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int |  |
| دفق | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف. |
| كلمة المرور | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | قائمة الصفحات للعرض. |
| الحجم | long | حجم الملف. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


ينشئ نسخة جديدة من الفئة [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع الملف. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | قائمة الصفحات للعرض. |
| الحجم | long | حجم الملف. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


فهرس المستند.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


تيار المستند.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة مرور المستند.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


يحصل على نوع الملف.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


يحدد مجموعة صفحات المستند.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


عدد صفحات المستند.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


حجم المستند بالبايت

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


يعيد سلسلة تمثل الكائن الحالي.

**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي.
