---
title: "DocumentInfo"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Definiert Dokumentbeschreibungs‑Eigenschaften."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definiert Dokumentbeschreibungs‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialisiert eine neue Instanz der Klasse [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIndex()](#getIndex--) | Der Dokumentindex. |
| [getStream()](#getStream--) | Der Dokumenten-Stream. |
| [getPassword()](#getPassword--) | Das Dokumentpasswort. |
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
| Größe | long | Die Größe der Datei. |

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
| Größe | long | Die Größe der Datei. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Der Dokumentindex.

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


Das Dokumentpasswort.

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
long
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.

**Returns:**
java.lang.String - Eine Zeichenkette, die das aktuelle Objekt darstellt.
