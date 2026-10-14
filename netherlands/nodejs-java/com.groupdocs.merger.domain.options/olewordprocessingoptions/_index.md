---
title: "OleWordProcessingOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het importeren van het ingebedde document naar Wordverwerking via OLE."
type: docs
weight: 21
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Biedt opties voor het importeren van het ingebedde document naar Wordverwerking via OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Initialiseert een nieuw exemplaar van de klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Initialiseert een nieuw exemplaar van de klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Initialiseert een nieuw exemplaar van de klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLeft()](#getLeft--) | De linkse coördinaat van de Ole-objectafbeelding. |
| [setLeft(int value)](#setLeft-int-) | De linkse coördinaat van de Ole-objectafbeelding. |
| [getTop()](#getTop--) | De bovenste coördinaat van de Ole-objectafbeelding. |
| [setTop(int value)](#setTop-int-) | De bovenste coördinaat van de Ole-objectafbeelding. |
| [getWidth()](#getWidth--) | De breedte van de Ole-objectafbeelding. |
| [setWidth(int value)](#setWidth-int-) | De breedte van de Ole-objectafbeelding. |
| [getHeight()](#getHeight--) | De hoogte van de Ole-objectafbeelding. |
| [setHeight(int value)](#setHeight-int-) | De hoogte van de Ole-objectafbeelding. |
| [getImageData()](#getImageData--) | De gegevens van de Ole‑objectafbeelding. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objectData | byte[] | De gegevens van het ingesloten object. |
| imageData | byte[] | De afbeeldingsgegevens van het ingesloten object. |
| extensie | java.lang.String | De extensie van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| imageData | byte[] | De afbeeldingsgegevens van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


De linkse coördinaat van de Ole-objectafbeelding.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


De linkse coördinaat van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


De bovenste coördinaat van de Ole-objectafbeelding.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


De bovenste coördinaat van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


De breedte van de Ole-objectafbeelding.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


De breedte van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


De hoogte van de Ole-objectafbeelding.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


De hoogte van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


De gegevens van de Ole‑objectafbeelding.

**Returns:**
byte[]
