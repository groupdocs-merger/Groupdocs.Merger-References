---
title: "IOleWordProcessingOptions"
second_title: "GroupDocs.Merger för Java API-referens"
description: "Gränssnitt för importalternativ för det inbäddade dokumentet till Ordbehandling via OLE."
type: docs
weight: 20
url: /sv/java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Gränssnitt för importalternativ för det inbäddade dokumentet till Ordbehandling via OLE.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLeft()](#getLeft--) | Den vänstra koordinaten för Ole‑objektbilden. |
| [setLeft(int value)](#setLeft-int-) | Den vänstra koordinaten för Ole‑objektbilden. |
| [getTop()](#getTop--) | Den övre koordinaten för Ole‑objektbilden. |
| [setTop(int value)](#setTop-int-) | Den övre koordinaten för Ole‑objektbilden. |
| [getImageData()](#getImageData--) | Data för Ole-objektbilden. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Den vänstra koordinaten för Ole‑objektbilden.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Den vänstra koordinaten för Ole‑objektbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Den övre koordinaten för Ole‑objektbilden.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Den övre koordinaten för Ole‑objektbilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Data för Ole-objektbilden.

**Returns:**
byte[]
