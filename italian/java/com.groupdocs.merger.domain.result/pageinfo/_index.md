---
title: "PageInfo"
second_title: "Riferimento API di GroupDocs.Merger per Java"
description: "Definisce le proprietà di descrizione della pagina."
type: docs
weight: 11
url: /it/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Definisce le proprietà di descrizione della pagina.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Inizializza una nuova istanza della classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Inizializza una nuova istanza della classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDocument()](#getDocument--) | Ottiene le informazioni del documento. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Ottiene le informazioni del documento. |
| [getNumber()](#getNumber--) | Ottiene il numero della pagina. |
| [getVisible()](#getVisible--) | Indica se la pagina è visibile o meno. |
| [getWidth()](#getWidth--) | Ottiene la larghezza della pagina in pixel quando convertita in immagine. |
| [getHeight()](#getHeight--) | Ottiene l'altezza della pagina in pixel quando convertita in immagine. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Inizializza una nuova istanza della classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero della pagina. |
| visibile | boolean | L'indicatore di visibilità della pagina. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Inizializza una nuova istanza della classe [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| numero | int | Il numero della pagina. |
| visibile | boolean | L'indicatore di visibilità della pagina. |
| larghezza | int | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| altezza | int | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Ottiene le informazioni del documento.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Ottiene le informazioni del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Ottiene il numero della pagina.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Indica se la pagina è visibile o meno.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza della pagina in pixel quando convertita in immagine.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza della pagina in pixel quando convertita in immagine.

**Returns:**
int
