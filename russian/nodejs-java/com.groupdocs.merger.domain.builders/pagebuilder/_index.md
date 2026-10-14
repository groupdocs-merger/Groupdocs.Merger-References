---
title: "PageBuilder"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "com.groupdocs.merger.licensing.metered"
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

com.groupdocs.merger.licensing.metered
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Инициализирует новый экземпляр класса [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Инициализирует новый экземпляр класса [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Методы

| Метод | Описание |
| --- | --- |
| [getOptions()](#getOptions--) | Параметры построителя страниц. |
| [getPages()](#getPages--) | Коллекция страниц. |
| [getDocuments()](#getDocuments--) | Коллекция документов. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Добавить документ в коллекцию документов. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Добавить документ в коллекцию документов. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Добавить страницу в коллекцию страниц. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Добавить страницу в коллекцию страниц. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Добавить страницы в коллекцию страниц. |
| [clear()](#clear--) | Очистить внутренние коллекции. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Инициализирует новый экземпляр класса [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Инициализирует новый экземпляр класса [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Параметры построителя страниц. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Параметры построителя страниц.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Коллекция страниц.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


Коллекция документов.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Добавить документ в коллекцию документов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс DocumentInfo. |
| поток | java.io.InputStream | Поток DocumentInfo. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Тип DocumentInfo. |
| пароль | java.lang.String | Пароль DocumentInfo. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Добавить документ в коллекцию документов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | Экземпляр DocumentInfo. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Добавить страницу в коллекцию страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentIndex | int | Индекс DocumentInfo. |
| pageNumber | int | номер PageInfo. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Добавить страницу в коллекцию страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | экземпляр PageInfo. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Добавить страницы в коллекцию страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | массив Pages. |

### clear() {#clear--}
```
public final void clear()
```


Очистить внутренние коллекции.

