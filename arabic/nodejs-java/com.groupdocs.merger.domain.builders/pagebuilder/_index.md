---
title: "PageBuilder"
second_title: "يوفر الفضاء الاسمي com.groupdocs.merger.domain.builders منشئات."
description: "com.groupdocs.merger.licensing.metered"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

com.groupdocs.merger.licensing.metered
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | يُنشئ مثلاً جديداً من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | يُنشئ مثلاً جديداً من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getOptions()](#getOptions--) | خيارات مُنشئ الصفحات. |
| [getPages()](#getPages--) | مجموعة الصفحات. |
| [getDocuments()](#getDocuments--) | مجموعة المستندات. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | أضف مستندًا إلى مجموعة المستندات. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | أضف مستندًا إلى مجموعة المستندات. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | أضف صفحةً إلى مجموعة الصفحات. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | أضف صفحةً إلى مجموعة الصفحات. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | أضف صفحات إلى مجموعة الصفحات. |
| [clear()](#clear--) | امسح المجموعات الداخلية. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


يُنشئ مثلاً جديداً من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


يُنشئ مثلاً جديداً من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | خيارات مُنشئ الصفحات. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


خيارات مُنشئ الصفحات.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


مجموعة الصفحات.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


مجموعة المستندات.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


أضف مستندًا إلى مجموعة المستندات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | int | فهرس DocumentInfo. |
| دفق | java.io.InputStream | دفق DocumentInfo. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | نوع DocumentInfo. |
| كلمة المرور | java.lang.String | كلمة مرور DocumentInfo. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


أضف مستندًا إلى مجموعة المستندات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | مثيل DocumentInfo. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


أضف صفحةً إلى مجموعة الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentIndex | int | فهرس DocumentInfo. |
| pageNumber | int | رقم PageInfo. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


أضف صفحةً إلى مجموعة الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | مثال PageInfo. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


أضف صفحات إلى مجموعة الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | مصفوفة Pages. |

### clear() {#clear--}
```
public final void clear()
```


امسح المجموعات الداخلية.

