---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für Importoptionen des eingebetteten Dokuments zu Diagramm via OLE."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Schnittstelle für Importoptionen des eingebetteten Dokuments zu Diagramm via OLE.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getX()](#getX--) | Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [setX(int value)](#setX-int-) | Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [getY()](#getY--) | Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [setY(int value)](#setY-int-) | Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite. |
| [getImageData()](#getImageData--) | Die Bilddaten des eingebetteten Objekts. |
### getX() {#getX--}
```
public abstract int getX()
```


Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


Die X‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Die Y‑Koordinate des Pin‑Punkts der Form des eingebetteten Objekts (Rotationszentrum) in Bezug auf die Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Die Bilddaten des eingebetteten Objekts.

**Returns:**
byte[]
