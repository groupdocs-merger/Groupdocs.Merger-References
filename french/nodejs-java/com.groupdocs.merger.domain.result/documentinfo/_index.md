---
title: "DocumentInfo"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Définit les propriétés de description du document."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Définit les propriétés de description du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIndex()](#getIndex--) | L'index du document. |
| [getStream()](#getStream--) | Le flux du document. |
| [getPassword()](#getPassword--) | Le mot de passe du document. |
| [getType()](#getType--) | Obtient le type de fichier. |
| [getPages()](#getPages--) | Définit la collection des pages du document. |
| [getPageCount()](#getPageCount--) | Le nombre de pages du document. |
| [getSize()](#getSize--) | Taille du document en octets |
| [toString()](#toString--) | Renvoie une chaîne qui représente l’objet actuel. |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |
| flux | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier. |
| mot de passe | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int |  |
| flux | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier. |
| mot de passe | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | La liste des pages à afficher. |
| taille | long | La taille du fichier. |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


Initialise une nouvelle instance de la classe [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type du fichier. |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | La liste des pages à afficher. |
| taille | long | La taille du fichier. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


L'index du document.

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


Le flux du document.

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Le mot de passe du document.

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


Obtient le type de fichier.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


Définit la collection des pages du document.

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Le nombre de pages du document.

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Taille du document en octets

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l’objet actuel.

**Returns:**
java.lang.String - Une chaîne qui représente l'objet actuel.
