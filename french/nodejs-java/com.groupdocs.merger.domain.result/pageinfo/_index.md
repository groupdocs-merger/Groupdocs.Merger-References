---
title: "PageInfo"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Définit les propriétés de description de la page."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Définit les propriétés de description de la page.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Initialise une nouvelle instance de la classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Initialise une nouvelle instance de la classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDocument()](#getDocument--) | Obtient les informations du document. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Obtient les informations du document. |
| [getNumber()](#getNumber--) | Obtient le numéro de page. |
| [getVisible()](#getVisible--) | Indique si la page est visible ou non. |
| [getWidth()](#getWidth--) | Obtient la largeur de la page en pixels lorsqu'elle est convertie en image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de la page en pixels lorsqu'elle est convertie en image. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Initialise une nouvelle instance de la classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| numéro | int | Le numéro de la page. |
| visible | boolean | L'indicateur de visibilité de la page. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Initialise une nouvelle instance de la classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| numéro | int | Le numéro de la page. |
| visible | boolean | L'indicateur de visibilité de la page. |
| largeur | int | La largeur de la page en pixels lors de l'affichage en JPG ou PNG. |
| hauteur | int | La hauteur de la page en pixels lors de l'affichage en JPG ou PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Obtient les informations du document.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Obtient les informations du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Obtient le numéro de page.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Indique si la page est visible ou non.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur de la page en pixels lorsqu'elle est convertie en image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur de la page en pixels lorsqu'elle est convertie en image.

**Returns:**
int
