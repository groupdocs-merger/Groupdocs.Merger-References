---
title: "PageInfo"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Definiert Seitenbeschreibungs‑Eigenschaften."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Definiert Seitenbeschreibungs‑Eigenschaften.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Initialisiert eine neue Instanz der Klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Initialisiert eine neue Instanz der Klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDocument()](#getDocument--) | Ermittelt die Dokumentinformationen. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Ermittelt die Dokumentinformationen. |
| [getNumber()](#getNumber--) | Ruft die Seitenzahl ab. |
| [getVisible()](#getVisible--) | Gibt an, ob die Seite sichtbar ist oder nicht. |
| [getWidth()](#getWidth--) | Ruft die Seitenbreite in Pixeln ab, wenn sie in ein Bild konvertiert wird. |
| [getHeight()](#getHeight--) | Ruft die Seitenhöhe in Pixeln ab, wenn sie in ein Bild konvertiert wird. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Initialisiert eine neue Instanz der Klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nummer | int | Die Seitenzahl. |
| sichtbar | boolean | Der Sichtbarkeitsindikator der Seite. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Initialisiert eine neue Instanz der Klasse [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nummer | int | Die Seitenzahl. |
| sichtbar | boolean | Der Sichtbarkeitsindikator der Seite. |
| Breite | int | Die Breite der Seite in Pixeln beim Anzeigen als JPG oder PNG. |
| Höhe | int | Die Höhe der Seite in Pixeln beim Anzeigen als JPG oder PNG. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Ermittelt die Dokumentinformationen.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Ermittelt die Dokumentinformationen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Ruft die Seitenzahl ab.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Gibt an, ob die Seite sichtbar ist oder nicht.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ruft die Seitenbreite in Pixeln ab, wenn sie in ein Bild konvertiert wird.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ruft die Seitenhöhe in Pixeln ab, wenn sie in ein Bild konvertiert wird.

**Returns:**
int
