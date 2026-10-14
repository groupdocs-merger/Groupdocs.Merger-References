---
title: "OleDiagramOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het importeren van het ingebedde document naar Diagram via OLE."
type: docs
weight: 18
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Biedt opties voor het importeren van het ingebedde document naar Diagram via OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Initialiseert een nieuw exemplaar van de [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) klasse. |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Initialiseert een nieuw exemplaar van de [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) klasse. |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Initialiseert een nieuw exemplaar van de [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getX()](#getX--) | De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [setX(int value)](#setX-int-) | De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [getY()](#getY--) | De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [setY(int value)](#setY-int-) | De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [getWidth()](#getWidth--) | De breedte van de ingesloten objectvorm in inches. |
| [setWidth(int value)](#setWidth-int-) | De breedte van de ingesloten objectvorm in inches. |
| [getHeight()](#getHeight--) | De hoogte van de ingesloten objectvorm in inches. |
| [setHeight(int value)](#setHeight-int-) | De hoogte van de ingesloten objectvorm in inches. |
| [getImageData()](#getImageData--) | De afbeeldingsgegevens van het ingesloten object. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objectData | byte[] | De gegevens van het ingesloten object. |
| imageData | byte[] | De afbeeldingsgegevens van het ingesloten object. |
| extensie | java.lang.String | De extensie van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| imageData | byte[] | De afbeeldingsgegevens van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### getX() {#getX--}
```
public final int getX()
```


De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


De breedte van de ingesloten objectvorm in inches.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


De breedte van de ingesloten objectvorm in inches.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


De hoogte van de ingesloten objectvorm in inches.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


De hoogte van de ingesloten objectvorm in inches.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


De afbeeldingsgegevens van het ingesloten object.

**Returns:**
byte[]
