---
title: "PageBuilder"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "PageInfo 构建器用于获取文档中的页面集合。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

PageInfo 构建器用于获取文档中的页面集合。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | 初始化 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 类的新实例。 |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | 初始化 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getOptions()](#getOptions--) | 页面构建器选项。 |
| [getPages()](#getPages--) | 页面集合。 |
| [getDocuments()](#getDocuments--) | 文档集合。 |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | 将文档添加到文档集合中。 |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | 将文档添加到文档集合中。 |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | 将页面添加到页面集合中。 |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | 将页面添加到页面集合中。 |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | 将页面添加到页面集合中。 |
| [clear()](#clear--) | 清除内部集合。 |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


初始化 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 类的新实例。

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


初始化 [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | 页面构建器选项。 |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


页面构建器选项。

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


页面集合。

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


文档集合。

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


将文档添加到文档集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | DocumentInfo 索引。 |
| 流 | java.io.InputStream | DocumentInfo 流。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo 类型。 |
| 密码 | java.lang.String | DocumentInfo 密码。 |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


将文档添加到文档集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo 实例。 |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


将页面添加到页面集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentIndex | int | DocumentInfo 索引。 |
| pageNumber | int | PageInfo 编号。 |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


将页面添加到页面集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo 实例。 |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


将页面添加到页面集合中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages 数组。 |

### clear() {#clear--}
```
public final void clear()
```


清除内部集合。

