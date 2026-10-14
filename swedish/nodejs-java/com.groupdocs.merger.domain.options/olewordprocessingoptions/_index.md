---
title: "OleWordProcessingOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för import av inbäddat dokument till Ordbehandling via OLE."
type: docs
weight: 21
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Tillhandahåller alternativ för import av inbäddat dokument till Ordbehandling via OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Initierar en ny instans av klassen [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Initierar en ny instans av klassen [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Initierar en ny instans av klassen [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLeft()](#getLeft--) | Den vänstra koordinaten för Ole‑objektets bild. |
| [setLeft(int value)](#setLeft-int-) | Den vänstra koordinaten för Ole‑objektets bild. |
| [getTop()](#getTop--) | Den övre koordinaten för Ole‑objektets bild. |
| [setTop(int value)](#setTop-int-) | Den övre koordinaten för Ole‑objektets bild. |
| [getWidth()](#getWidth--) | Bredden på Ole-objektets bild. |
| [setWidth(int value)](#setWidth-int-) | Bredden på Ole-objektets bild. |
| [getHeight()](#getHeight--) | Höjden på Ole-objektets bild. |
| [setHeight(int value)](#setHeight-int-) | Höjden på Ole-objektets bild. |
| [getImageData()](#getImageData--) | Data för Ole-objektets bild. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initierar en ny instans av klassen [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectData | byte[] | Data för det inbäddade objektet. |
| imageData | byte[] | Bilddata för det inbäddade objektet. |
| filändelse | java.lang.String | Filändelse för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Initierar en ny instans av klassen [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| imageData | byte[] | Bilddata för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Initierar en ny instans av klassen [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Den vänstra koordinaten för Ole‑objektets bild.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Den vänstra koordinaten för Ole‑objektets bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Den övre koordinaten för Ole‑objektets bild.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Den övre koordinaten för Ole‑objektets bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bredden på Ole-objektets bild.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bredden på Ole-objektets bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höjden på Ole-objektets bild.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höjden på Ole-objektets bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Data för Ole-objektets bild.

**Returns:**
byte[]
