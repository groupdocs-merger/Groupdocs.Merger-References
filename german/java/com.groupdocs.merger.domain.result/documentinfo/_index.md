---
title: "DocumentInfo"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Definiert Eigenschaften der Dokumentbeschreibung."
type: docs
weight: 10
url: /de/java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definiert Eigenschaften der Dokumentbeschreibung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIndex()](#getIndex--) | Der Dokumentenindex. |
| [getStream()](#getStream--) | Der Dokumenten-Stream. |
| [getPassword()](#getPassword--) | Das Dokumentenkennwort. |
| [getType()](#getType--) | Ermittelt den Dateityp. |
| [getPages()](#getPages--) | Definiert die Sammlung von Dokumentseiten. |
| [getPageCount()](#getPageCount--) | Die Anzahl der Dokumentseiten. |
| [getSize()](#getSize--) | Dokumentgröße in Bytes |
| [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int |  |
| Stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der Datei. |
| Passwort | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int |  |
| Stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der Datei. |
| Passwort | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Die Liste der anzuzeigenden Seiten. |
| Größe | lang | Die Größe der Datei. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der Datei. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Die Liste der anzuzeigenden Seiten. |
| Größe | lang | Die Größe der Datei. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Der Dokumentenindex.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Der Dokumenten-Stream.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Das Dokumentenkennwort.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Ermittelt den Dateityp.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Definiert die Sammlung von Dokumentseiten.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Die Anzahl der Dokumentseiten.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Dokumentgröße in Bytes

**Returns:**
lang
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.

**Returns:**
java.lang.String - Eine Zeichenkette, die das aktuelle Objekt darstellt.
