---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für den Import des eingebetteten Dokuments in die Textverarbeitung via OLE."
type: docs
weight: 21
url: /de/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Bietet Optionen für den Import des eingebetteten Dokuments in die Textverarbeitung via OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Initialisiert eine neue Instanz der Klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Initialisiert eine neue Instanz der Klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Initialisiert eine neue Instanz der Klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeft()](#getLeft--) | Die linke Koordinate des Ole-Objekt-Bildes. |
| [setLeft(int value)](#setLeft-int-) | Die linke Koordinate des Ole-Objekt-Bildes. |
| [getTop()](#getTop--) | Die obere Koordinate des Ole-Objekt-Bildes. |
| [setTop(int value)](#setTop-int-) | Die obere Koordinate des Ole-Objekt-Bildes. |
| [getWidth()](#getWidth--) | Die Breite des Ole-Objektbildes. |
| [setWidth(int value)](#setWidth-int-) | Die Breite des Ole-Objektbildes. |
| [getHeight()](#getHeight--) | Die Höhe des Ole-Objektbildes. |
| [setHeight(int value)](#setHeight-int-) | Die Höhe des Ole-Objektbildes. |
| [getImageData()](#getImageData--) | Die Daten des Ole-Objektbildes. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialisiert eine neue Instanz der Klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectData | byte[] | Die Daten des eingebetteten Objekts. |
| imageData | byte[] | Die Bilddaten des eingebetteten Objekts. |
| Erweiterung | java.lang.String | Die Erweiterung des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialisiert eine neue Instanz der Klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| imageData | byte[] | Die Bilddaten des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Initialisiert eine neue Instanz der Klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Die linke Koordinate des Ole-Objekt-Bildes.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Die linke Koordinate des Ole-Objekt-Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Die obere Koordinate des Ole-Objekt-Bildes.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Die obere Koordinate des Ole-Objekt-Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Die Breite des Ole-Objektbildes.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Die Breite des Ole-Objektbildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Die Höhe des Ole-Objektbildes.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Die Höhe des Ole-Objektbildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Die Daten des Ole-Objektbildes.

**Returns:**
byte[]
