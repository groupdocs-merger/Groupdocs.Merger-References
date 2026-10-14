---
title: "OleDiagramOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för import av inbäddat dokument till Diagram via OLE."
type: docs
weight: 18
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Tillhandahåller alternativ för import av inbäddat dokument till Diagram via OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Initierar en ny instans av klassen [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Initierar en ny instans av klassen [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Initierar en ny instans av klassen [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [setX(int value)](#setX-int-) | X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [getY()](#getY--) | Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [setY(int value)](#setY-int-) | Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [getWidth()](#getWidth--) | Bredden på den inbäddade objektsformen i tum. |
| [setWidth(int value)](#setWidth-int-) | Bredden på den inbäddade objektsformen i tum. |
| [getHeight()](#getHeight--) | Höjden på den inbäddade objektsformen i tum. |
| [setHeight(int value)](#setHeight-int-) | Höjden på den inbäddade objektsformen i tum. |
| [getImageData()](#getImageData--) | Bilddata för det inbäddade objektet. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initierar en ny instans av klassen [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectData | byte[] | Data för det inbäddade objektet. |
| imageData | byte[] | Bilddata för det inbäddade objektet. |
| filändelse | java.lang.String | Filändelse för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Initierar en ny instans av klassen [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| imageData | byte[] | Bilddata för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Initierar en ny instans av klassen [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### getX() {#getX--}
```
public final int getX()
```


X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bredden på den inbäddade objektsformen i tum.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bredden på den inbäddade objektsformen i tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höjden på den inbäddade objektsformen i tum.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höjden på den inbäddade objektsformen i tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Bilddata för det inbäddade objektet.

**Returns:**
byte[]
