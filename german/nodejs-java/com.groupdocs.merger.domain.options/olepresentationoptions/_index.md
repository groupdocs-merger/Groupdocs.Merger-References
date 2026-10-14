---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für den Import des eingebetteten Dokuments in Präsentationen via OLE."
type: docs
weight: 19
url: /de/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Bietet Optionen für den Import des eingebetteten Dokuments in Präsentationen via OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Initialisiert eine neue Instanz der [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) Klasse. |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Initialisiert eine neue Instanz der [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getX()](#getX--) | Die X-Koordinate des eingebetteten Objektrahmens. |
| [setX(int value)](#setX-int-) | Die X-Koordinate des eingebetteten Objektrahmens. |
| [getY()](#getY--) | Die Y-Koordinate des eingebetteten Objektrahmens. |
| [setY(int value)](#setY-int-) | Die Y-Koordinate des eingebetteten Objektrahmens. |
| [getWidth()](#getWidth--) | Die Breite des eingebetteten Objektrahmens. |
| [setWidth(int value)](#setWidth-int-) | Die Breite des eingebetteten Objektrahmens. |
| [getHeight()](#getHeight--) | Die Höhe des eingebetteten Objektrahmens. |
| [setHeight(int value)](#setHeight-int-) | Die Höhe des eingebetteten Objektrahmens. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Initialisiert eine neue Instanz der [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectData | byte[] | Die Daten des eingebetteten Objekts. |
| Erweiterung | java.lang.String | Die Erweiterung des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Initialisiert eine neue Instanz der [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### getX() {#getX--}
```
public final int getX()
```


Die X-Koordinate des eingebetteten Objektrahmens.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Die X-Koordinate des eingebetteten Objektrahmens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Die Y-Koordinate des eingebetteten Objektrahmens.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Die Y-Koordinate des eingebetteten Objektrahmens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Die Breite des eingebetteten Objektrahmens.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Die Breite des eingebetteten Objektrahmens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Die Höhe des eingebetteten Objektrahmens.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Die Höhe des eingebetteten Objektrahmens.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

