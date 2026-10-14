---
title: "IOleWordProcessingOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor importopties van het ingesloten document naar Wordverwerking via OLE."
type: docs
weight: 20
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Interface voor importopties van het ingesloten document naar Wordverwerking via OLE.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLeft()](#getLeft--) | De linkse coördinaat van de Ole-objectafbeelding. |
| [setLeft(int value)](#setLeft-int-) | De linkse coördinaat van de Ole-objectafbeelding. |
| [getTop()](#getTop--) | De bovenste coördinaat van de Ole-objectafbeelding. |
| [setTop(int value)](#setTop-int-) | De bovenste coördinaat van de Ole-objectafbeelding. |
| [getImageData()](#getImageData--) | De gegevens van de Ole‑objectafbeelding. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


De linkse coördinaat van de Ole-objectafbeelding.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


De linkse coördinaat van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


De bovenste coördinaat van de Ole-objectafbeelding.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


De bovenste coördinaat van de Ole-objectafbeelding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


De gegevens van de Ole‑objectafbeelding.

**Returns:**
byte[]
