---
title: "IOleWordProcessingOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für Importoptionen des eingebetteten Dokuments zu Textverarbeitung via OLE."
type: docs
weight: 20
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Schnittstelle für Importoptionen des eingebetteten Dokuments zu Textverarbeitung via OLE.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeft()](#getLeft--) | Die linke Koordinate des Ole-Objekt-Bildes. |
| [setLeft(int value)](#setLeft-int-) | Die linke Koordinate des Ole-Objekt-Bildes. |
| [getTop()](#getTop--) | Die obere Koordinate des Ole-Objekt-Bildes. |
| [setTop(int value)](#setTop-int-) | Die obere Koordinate des Ole-Objekt-Bildes. |
| [getImageData()](#getImageData--) | Die Daten des Ole-Objektbildes. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Die linke Koordinate des Ole-Objekt-Bildes.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Die linke Koordinate des Ole-Objekt-Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Die obere Koordinate des Ole-Objekt-Bildes.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Die obere Koordinate des Ole-Objekt-Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Die Daten des Ole-Objektbildes.

**Returns:**
byte[]
