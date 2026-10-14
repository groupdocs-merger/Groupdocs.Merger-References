---
title: "DocumentInfo"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Definieert documentbeschrijvingseigenschappen."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definieert documentbeschrijvingseigenschappen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klasse. |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klasse. |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getIndex()](#getIndex--) | De documentindex. |
| [getStream()](#getStream--) | De documentstroom. |
| [getPassword()](#getPassword--) | Het documentwachtwoord. |
| [getType()](#getType--) | Haalt het bestandstype op. |
| [getPages()](#getPages--) | Definieert de collectie documentpagina's. |
| [getPageCount()](#getPageCount--) | Het aantal documentpagina's. |
| [getSize()](#getSize--) | Documentgrootte in bytes |
| [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand. |
| password | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand. |
| password | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | De lijst met pagina's om te bekijken. |
| grootte | long | De grootte van het bestand. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | De lijst met pagina's om te bekijken. |
| grootte | long | De grootte van het bestand. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


De documentindex.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


De documentstroom.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Het documentwachtwoord.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Haalt het bestandstype op.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Definieert de collectie documentpagina's.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Het aantal documentpagina's.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Documentgrootte in bytes

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.

**Returns:**
java.lang.String - Een string die het huidige object vertegenwoordigt.
