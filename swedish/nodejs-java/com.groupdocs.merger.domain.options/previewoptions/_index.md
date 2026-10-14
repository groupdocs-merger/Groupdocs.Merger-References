---
title: "PreviewOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Representerar alternativ för dokumentförhandsgranskning."
type: docs
weight: 29
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Representerar alternativ för dokumentförhandsgranskning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Förhandsgranskningsbredd. |
| [setWidth(int value)](#setWidth-int-) | Förhandsgranskningsbredd. |
| [getHeight()](#getHeight--) | Förhandsgranskningshöjd. |
| [setHeight(int value)](#setHeight-int-) | Förhandsgranskningshöjd. |
| [getResolution()](#getResolution--) | Bildupplösning. |
| [setResolution(int value)](#setResolution-int-) | Bildupplösning. |
| [getMode()](#getMode--) | Läge för förhandsgranskning. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validerar förhandsgranskningsalternativen. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Hämtar den fullständiga filsökvägen för det förhandsgranskade dokumentet efter sidnummer med definierad filändelse. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory för att skapa eller frigöra utdata sidförhandsgranskningsström. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| previewMode | int | Förhandsgranskningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| previewMode | int | Förhandsgranskningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Sidnummer. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| previewMode | int | Förhandsgranskningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metoden som instansierar strömmen som används för att skriva utdata siddata. |
| previewMode | int | Förhandsgranskningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |
| mode | int | Områdesläget. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Förhandsgranskningsbredd.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Förhandsgranskningsbredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Förhandsgranskningshöjd.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Förhandsgranskningshöjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Bildupplösning.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Bildupplösning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Läge för förhandsgranskning.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validerar förhandsgranskningsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filtypen. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory för att skapa eller frigöra utdata sidförhandsgranskningsström.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
