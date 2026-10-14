---
title: "PageInfo"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Define propiedades de descripción de página."
type: docs
weight: 11
url: /es/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Define propiedades de descripción de página.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Inicializa una nueva instancia de la clase [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Inicializa una nueva instancia de la clase [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDocument()](#getDocument--) | Obtiene la información del documento. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Obtiene la información del documento. |
| [getNumber()](#getNumber--) | Obtiene el número de página. |
| [getVisible()](#getVisible--) | Indica si la página es visible o no. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la página en píxeles al convertirla a imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la página en píxeles al convertirla a imagen. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Inicializa una nueva instancia de la clase [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| número | int | El número de página. |
| visible | boolean | El indicador de visibilidad de la página. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Inicializa una nueva instancia de la clase [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| número | int | El número de página. |
| visible | boolean | El indicador de visibilidad de la página. |
| ancho | int | El ancho de la página en píxeles al verla como JPG o PNG. |
| altura | int | La altura de la página en píxeles al verla como JPG o PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Obtiene la información del documento.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Obtiene la información del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Obtiene el número de página.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Indica si la página es visible o no.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de la página en píxeles al convertirla a imagen.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de la página en píxeles al convertirla a imagen.

**Returns:**
int
