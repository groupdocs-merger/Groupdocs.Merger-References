---
title: "DocumentInfo"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Definisce le proprietà di descrizione del documento."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definisce le proprietà di descrizione del documento.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIndex()](#getIndex--) | L'indice del documento. |
| [getStream()](#getStream--) | Il flusso del documento. |
| [getPassword()](#getPassword--) | La password del documento. |
| [getType()](#getType--) | Ottiene il tipo di file. |
| [getPages()](#getPages--) | Definisce la collezione di pagine del documento. |
| [getPageCount()](#getPageCount--) | Il conteggio delle pagine del documento. |
| [getSize()](#getSize--) | Dimensione del documento in byte |
| [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |
| flusso | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file. |
| password | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |
| flusso | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file. |
| password | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | L'elenco delle pagine da visualizzare. |
| dimensione | long | La dimensione del file. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Il tipo del file. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | L'elenco delle pagine da visualizzare. |
| dimensione | long | La dimensione del file. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


L'indice del documento.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Il flusso del documento.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


La password del documento.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Ottiene il tipo di file.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Definisce la collezione di pagine del documento.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Il conteggio delle pagine del documento.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Dimensione del documento in byte

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
java.lang.String - Una stringa che rappresenta l'oggetto corrente.
