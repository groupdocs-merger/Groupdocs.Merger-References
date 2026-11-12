---
title: "PageInfo"
second_title: "GroupDocs.Merger för Java API-referens"
description: "Definierar egenskaper för sidbeskrivning."
type: docs
weight: 11
url: /sv/java/com.groupdocs.merger.domain.result/pageinfo/
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
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Initierar en ny instans av klassen [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Initierar en ny instans av klassen [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDocument()](#getDocument--) | Hämtar dokumentinformationen. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Hämtar dokumentinformationen. |
| [getNumber()](#getNumber--) | Hämtar sidnumret. |
| [getVisible()](#getVisible--) | Anger om sidan är synlig eller inte. |
| [getWidth()](#getWidth--) | Hämtar sidans bredd i pixlar när den konverteras till bild. |
| [getHeight()](#getHeight--) | Hämtar sidans höjd i pixlar när den konverteras till bild. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Initierar en ny instans av klassen [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | int | Sidnumret. |
| synlig | boolean | Sidans synlighetsindikator. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Initierar en ny instans av klassen [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nummer | int | Sidnumret. |
| synlig | boolean | Sidans synlighetsindikator. |
| bredd | int | Sidans bredd i pixlar när den visas som JPG eller PNG. |
| höjd | int | Sidans höjd i pixlar när den visas som JPG eller PNG. |

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


Anger om sidan är synlig eller inte.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar sidans bredd i pixlar när den konverteras till bild.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar sidans höjd i pixlar när den konverteras till bild.

**Returns:**
int
