---
title: "OlePresentationOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het importeren van het ingebedde document naar Presentatie via OLE."
type: docs
weight: 19
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Biedt opties voor het importeren van het ingebedde document naar Presentatie via OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Initialiseert een nieuw exemplaar van de [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) klasse. |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Initialiseert een nieuw exemplaar van de [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getX()](#getX--) | De X-coördinaat van het ingesloten objectframe. |
| [setX(int value)](#setX-int-) | De X-coördinaat van het ingesloten objectframe. |
| [getY()](#getY--) | De Y-coördinaat van het ingesloten objectframe. |
| [setY(int value)](#setY-int-) | De Y-coördinaat van het ingesloten objectframe. |
| [getWidth()](#getWidth--) | De breedte van het frame van het ingesloten object. |
| [setWidth(int value)](#setWidth-int-) | De breedte van het frame van het ingesloten object. |
| [getHeight()](#getHeight--) | De hoogte van het frame van het ingesloten object. |
| [setHeight(int value)](#setHeight-int-) | De hoogte van het frame van het ingesloten object. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objectData | byte[] | De gegevens van het ingesloten object. |
| extensie | java.lang.String | De extensie van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### getX() {#getX--}
```
public final int getX()
```


De X-coördinaat van het ingesloten objectframe.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


De X-coördinaat van het ingesloten objectframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


De Y-coördinaat van het ingesloten objectframe.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


De Y-coördinaat van het ingesloten objectframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


De breedte van het frame van het ingesloten object.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


De breedte van het frame van het ingesloten object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


De hoogte van het frame van het ingesloten object.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


De hoogte van het frame van het ingesloten object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

