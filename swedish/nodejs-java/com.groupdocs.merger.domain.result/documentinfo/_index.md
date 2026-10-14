---
title: "DocumentInfo"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Definierar egenskaper för dokumentbeskrivning."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definierar egenskaper för dokumentbeskrivning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initierar en ny instans av [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klassen. |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initierar en ny instans av [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klassen. |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initierar en ny instans av [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIndex()](#getIndex--) | Dokumentets index. |
| [getStream()](#getStream--) | Dokumentströmmen. |
| [getPassword()](#getPassword--) | Dokumentets lösenord. |
| [getType()](#getType--) | Hämtar filtypen. |
| [getPages()](#getPages--) | Definierar samling av dokumentets sidor. |
| [getPageCount()](#getPageCount--) | Antalet sidor i dokumentet. |
| [getSize()](#getSize--) | Dokumentstorlek i byte |
| [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Initierar en ny instans av [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| ström | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filens typ. |
| lösenord | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Initierar en ny instans av [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| ström | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filens typ. |
| lösenord | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Listan över sidor att visa. |
| storlek | long | Filens storlek. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Initierar en ny instans av [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filens typ. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Listan över sidor att visa. |
| storlek | long | Filens storlek. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Dokumentets index.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Dokumentströmmen.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Dokumentets lösenord.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Hämtar filtypen.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Definierar samling av dokumentets sidor.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Antalet sidor i dokumentet.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Dokumentstorlek i byte

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
java.lang.String - En sträng som representerar det aktuella objektet.
