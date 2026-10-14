---
title: "PageInfo"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Definierar egenskaper för sidbeskrivning."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Definierar egenskaper för sidbeskrivning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Initierar en ny instans av [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) klassen. |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Initierar en ny instans av [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDocument()](#getDocument--) | Hämtar dokumentinformationen. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Hämtar dokumentinformationen. |
| [getNumber()](#getNumber--) | Hämtar sidnumret. |
| [getVisible()](#getVisible--) | Indikerar om sidan är synlig eller inte. |
| [getWidth()](#getWidth--) | Hämtar sidbredd i pixlar när den konverteras till bild. |
| [getHeight()](#getHeight--) | Hämtar sidhöjd i pixlar när den konverteras till bild. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Initierar en ny instans av [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | int | Sidnumret. |
| synlig | boolean | Sidans synlighetsindikator. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Initierar en ny instans av [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | int | Sidnumret. |
| synlig | boolean | Sidans synlighetsindikator. |
| bredd | int | Bredden på sidan i pixlar när den visas som JPG eller PNG. |
| höjd | int | Höjden på sidan i pixlar när den visas som JPG eller PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Hämtar dokumentinformationen.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Hämtar dokumentinformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Hämtar sidnumret.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Indikerar om sidan är synlig eller inte.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar sidbredd i pixlar när den konverteras till bild.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar sidhöjd i pixlar när den konverteras till bild.

**Returns:**
int
