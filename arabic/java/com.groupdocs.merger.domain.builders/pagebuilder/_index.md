---
title: "PageBuilder"
second_title: "توفر مساحة الأسماء com.groupdocs.merger.domain.builders منشئين."
description: "com.groupdocs.merger.licensing.metered"
type: docs
weight: 10
url: /ar/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

com.groupdocs.merger.licensing.metered
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | يقوم بتهيئة نسخة جديدة من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | يقوم بتهيئة نسخة جديدة من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOptions()](#getOptions--) | خيارات مُنشئ الصفحة. |
| [getPages()](#getPages--) | مجموعة الصفحات. |
| [getDocuments()](#getDocuments--) | مجموعة المستندات. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | أضف مستندًا إلى مجموعة المستندات. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | أضف مستندًا إلى مجموعة المستندات. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | أضف صفحة إلى مجموعة الصفحات. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | أضف صفحة إلى مجموعة الصفحات. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | أضف صفحات إلى مجموعة الصفحات. |
| [clear()](#clear--) | امسح المجموعات الداخلية. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


يقوم بتهيئة نسخة جديدة من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


يقوم بتهيئة نسخة جديدة من الفئة [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | خيارات مُنشئ الصفحة. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


خيارات مُنشئ الصفحة.

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
| index | int | DocumentInfo فهرس. |
| stream | java.io.InputStream | DocumentInfo دفق. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo نوع. |
| كلمة المرور | java.lang.String | DocumentInfo كلمة المرور. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


أضف مستندًا إلى مجموعة المستندات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo مثيل. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


أضف صفحة إلى مجموعة الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentIndex | int | DocumentInfo فهرس. |
| pageNumber | int | PageInfo رقم. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


أضف صفحة إلى مجموعة الصفحات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo مثيل. |

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

