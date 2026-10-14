---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för import av inbäddat dokument till Presentation via OLE."
type: docs
weight: 19
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Tillhandahåller alternativ för import av inbäddat dokument till Presentation via OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Initierar en ny instans av klassen [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Initierar en ny instans av klassen [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | X-koordinaten för den inbäddade objektramen. |
| [setX(int value)](#setX-int-) | X-koordinaten för den inbäddade objektramen. |
| [getY()](#getY--) | Y-koordinaten för den inbäddade objektramen. |
| [setY(int value)](#setY-int-) | Y-koordinaten för den inbäddade objektramen. |
| [getWidth()](#getWidth--) | Bredden på den inbäddade objektramen. |
| [setWidth(int value)](#setWidth-int-) | Bredden på den inbäddade objektramen. |
| [getHeight()](#getHeight--) | Höjden på den inbäddade objektramen. |
| [setHeight(int value)](#setHeight-int-) | Höjden på den inbäddade objektramen. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Initierar en ny instans av klassen [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectData | byte[] | Data för det inbäddade objektet. |
| filändelse | java.lang.String | Filändelse för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Initierar en ny instans av klassen [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### getX() {#getX--}
```
public final int getX()
```


X-koordinaten för den inbäddade objektramen.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


X-koordinaten för den inbäddade objektramen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Y-koordinaten för den inbäddade objektramen.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Y-koordinaten för den inbäddade objektramen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bredden på den inbäddade objektramen.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Bredden på den inbäddade objektramen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Höjden på den inbäddade objektramen.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Höjden på den inbäddade objektramen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

