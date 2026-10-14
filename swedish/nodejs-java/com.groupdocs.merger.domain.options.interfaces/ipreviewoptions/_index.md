---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Gränssnitt för förhandsgranskningsalternativ."
type: docs
weight: 28
url: /sv/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Gränssnitt för förhandsgranskningsalternativ.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Förhandsgranskningsbredd. |
| [setWidth(int value)](#setWidth-int-) | Förhandsgranskningsbredd. |
| [getHeight()](#getHeight--) | Förhandsgranskningshöjd. |
| [setHeight(int value)](#setHeight-int-) | Förhandsgranskningshöjd. |
| [getResolution()](#getResolution--) | Bildupplösning. |
| [setResolution(int value)](#setResolution-int-) | Bildupplösning. |
| [getMode()](#getMode--) | Hämtar läget för förhandsgranskning. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validerar uppdelningsalternativen. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Hämtar den fullständiga filsökvägen för det förhandsgranskade dokumentet efter sidnummer med definierad filändelse. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegat som definierar metod för att skapa en utdata‑sidförhandsgranskningsström. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Förhandsgranskningsbredd.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Förhandsgranskningsbredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Förhandsgranskningshöjd.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Förhandsgranskningshöjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Bildupplösning.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Bildupplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Hämtar läget för förhandsgranskning.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Validerar uppdelningsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filtypen för klassen [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Hämtar den fullständiga filsökvägen för det förhandsgranskade dokumentet efter sidnummer med definierad filändelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumber | int | Sidnummer för förhandsgranskning. |
| filändelse | java.lang.String | Filändelse för filen. |

**Returns:**
java.lang.String - Den fullständiga filsökvägen.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Delegat som definierar metod för att skapa en utdata‑sidförhandsgranskningsström.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
