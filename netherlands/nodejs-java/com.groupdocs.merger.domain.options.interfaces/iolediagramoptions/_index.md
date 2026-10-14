---
title: "IOleDiagramOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor importopties van het ingesloten document naar Diagram via OLE."
type: docs
weight: 17
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Interface voor importopties van het ingesloten document naar Diagram via OLE.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getX()](#getX--) | De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [setX(int value)](#setX-int-) | De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [getY()](#getY--) | De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [setY(int value)](#setY-int-) | De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina. |
| [getImageData()](#getImageData--) | De afbeeldingsgegevens van het ingesloten object. |
### getX() {#getX--}
```
public abstract int getX()
```


De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


De X-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


De Y-coördinaat van de pin van de vorm van het ingesloten object (rotatiecentrum) ten opzichte van de pagina.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


De afbeeldingsgegevens van het ingesloten object.

**Returns:**
byte[]
