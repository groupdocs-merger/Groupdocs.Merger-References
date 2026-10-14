---
title: "OleDiagramOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für den Import des eingebetteten Dokuments in Diagramme via OLE."
type: docs
weight: 18
url: /de/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Bietet Optionen für den Import des eingebetteten Dokuments in Diagramme via OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Initialisiert eine neue Instanz der [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) Klasse. |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Initialisiert eine neue Instanz der [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) Klasse. |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Initialisiert eine neue Instanz der [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getX()](#getX--) | Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [setX(int value)](#setX-int-) | Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [getY()](#getY--) | Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [setY(int value)](#setY-int-) | Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [getWidth()](#getWidth--) | Die Breite der eingebetteten Objektform in Zoll. |
| [setWidth(int value)](#setWidth-int-) | Die Breite der eingebetteten Objektform in Zoll. |
| [getHeight()](#getHeight--) | Die Höhe der eingebetteten Objektform in Zoll. |
| [setHeight(int value)](#setHeight-int-) | Die Höhe der eingebetteten Objektform in Zoll. |
| [getImageData()](#getImageData--) | Die Bilddaten des eingebetteten Objekts. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialisiert eine neue Instanz der [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectData | byte[] | Die Daten des eingebetteten Objekts. |
| imageData | byte[] | Die Bilddaten des eingebetteten Objekts. |
| Erweiterung | java.lang.String | Die Erweiterung des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialisiert eine neue Instanz der [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| imageData | byte[] | Die Bilddaten des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Initialisiert eine neue Instanz der [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### getX() {#getX--}
```
public final int getX()
```


Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Die Breite der eingebetteten Objektform in Zoll.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Die Breite der eingebetteten Objektform in Zoll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Die Höhe der eingebetteten Objektform in Zoll.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Die Höhe der eingebetteten Objektform in Zoll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Die Bilddaten des eingebetteten Objekts.

**Returns:**
byte[]
