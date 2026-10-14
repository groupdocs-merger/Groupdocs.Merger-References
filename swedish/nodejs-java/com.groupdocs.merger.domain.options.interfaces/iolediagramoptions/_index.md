---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Gränssnitt för importalternativ för det inbäddade dokumentet till Diagram via OLE."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Gränssnitt för importalternativ för det inbäddade dokumentet till Diagram via OLE.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getX()](#getX--) | X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [setX(int value)](#setX-int-) | X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [getY()](#getY--) | Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [setY(int value)](#setY-int-) | Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan. |
| [getImageData()](#getImageData--) | Bilddata för det inbäddade objektet. |
### getX() {#getX--}
```
public abstract int getX()
```


X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


X-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Y-koordinaten för den inbäddade objektformen pinne (rotationscentrum) i förhållande till sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Bilddata för det inbäddade objektet.

**Returns:**
byte[]
