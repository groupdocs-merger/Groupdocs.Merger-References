---
title: "DocumentInfo"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Define propiedades de descripción del documento."
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Define propiedades de descripción del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIndex()](#getIndex--) | El índice del documento. |
| [getStream()](#getStream--) | El flujo del documento. |
| [getPassword()](#getPassword--) | La contraseña del documento. |
| [getType()](#getType--) | Obtiene el tipo de archivo. |
| [getPages()](#getPages--) | Define la colección de páginas del documento. |
| [getPageCount()](#getPageCount--) | El recuento de páginas del documento. |
| [getSize()](#getSize--) | Tamaño del documento en bytes |
| [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |
| flujo | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo del archivo. |
| contraseña | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |
| flujo | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo del archivo. |
| contraseña | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | La lista de páginas para ver. |
| tamaño | long | El tamaño del archivo. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El tipo del archivo. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | La lista de páginas para ver. |
| tamaño | long | El tamaño del archivo. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


El índice del documento.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


El flujo del documento.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


La contraseña del documento.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Obtiene el tipo de archivo.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Define la colección de páginas del documento.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


El recuento de páginas del documento.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Tamaño del documento en bytes

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.

**Returns:**
java.lang.String - Una cadena que representa el objeto actual.
