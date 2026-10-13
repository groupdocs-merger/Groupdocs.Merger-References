---
title: "PageInfo"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Definieert paginabeschrijvingseigenschappen."
type: docs
weight: 11
url: /nl/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Definieert paginabeschrijvingseigenschappen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Initialiseert een nieuw exemplaar van de klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Initialiseert een nieuw exemplaar van de klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDocument()](#getDocument--) | Haalt de documentinformatie op. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Haalt de documentinformatie op. |
| [getNumber()](#getNumber--) | Haalt het paginanummer op. |
| [getVisible()](#getVisible--) | Geeft aan of de pagina zichtbaar is of niet. |
| [getWidth()](#getWidth--) | Haalt de paginabreedte in pixels op wanneer geconverteerd naar een afbeelding. |
| [getHeight()](#getHeight--) | Haalt de paginahoogte in pixels op wanneer geconverteerd naar een afbeelding. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Initialiseert een nieuw exemplaar van de klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| visible | boolean | De paginazichtindicator. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Initialiseert een nieuw exemplaar van de klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| number | int | Het paginanummer. |
| visible | boolean | De paginazichtindicator. |
| width | int | De breedte van de pagina in pixels bij weergave als JPG of PNG. |
| height | int | De hoogte van de pagina in pixels bij weergave als JPG of PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Haalt de documentinformatie op.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Haalt de documentinformatie op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Haalt het paginanummer op.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Geeft aan of de pagina zichtbaar is of niet.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Haalt de paginabreedte in pixels op wanneer geconverteerd naar een afbeelding.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Haalt de paginahoogte in pixels op wanneer geconverteerd naar een afbeelding.

**Returns:**
int
