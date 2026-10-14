---
title: "PageBuilder"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Constructor PageInfo para obtener la colección de páginas de los documentos."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

Constructor PageInfo para obtener la colección de páginas de los documentos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | Inicializa una nueva instancia de la clase [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Inicializa una nueva instancia de la clase [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOptions()](#getOptions--) | Las opciones del generador de páginas. |
| [getPages()](#getPages--) | La colección de páginas. |
| [getDocuments()](#getDocuments--) | La colección de documentos. |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Agregar documento a la colección de documentos. |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Agregar documento a la colección de documentos. |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | Agregar página a la colección de páginas. |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | Agregar página a la colección de páginas. |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | Agregar páginas a la colección de páginas. |
| [clear()](#clear--) | Borrar las colecciones internas. |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


Inicializa una nueva instancia de la clase [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


Inicializa una nueva instancia de la clase [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | Las opciones del generador de páginas. |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


Las opciones del generador de páginas.

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


La colección de páginas.

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


La colección de documentos.

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


Agregar documento a la colección de documentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | Índice de DocumentInfo. |
| flujo | java.io.InputStream | Flujo de DocumentInfo. |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipo de DocumentInfo. |
| contraseña | java.lang.String | Contraseña de DocumentInfo. |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


Agregar documento a la colección de documentos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | Instancia de DocumentInfo. |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


Agregar página a la colección de páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documentIndex | int | Índice de DocumentInfo. |
| pageNumber | int | Número de PageInfo. |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


Agregar página a la colección de páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | Instancia de PageInfo. |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


Agregar páginas a la colección de páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Matriz de Pages. |

### clear() {#clear--}
```
public final void clear()
```


Borrar las colecciones internas.

