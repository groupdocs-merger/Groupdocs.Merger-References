---
title: "PreviewOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Stelt documentvoorbeeldopties voor."
type: docs
weight: 29
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Stelt documentvoorbeeldopties voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Breedte van voorbeeld. |
| [setWidth(int value)](#setWidth-int-) | Breedte van voorbeeld. |
| [getHeight()](#getHeight--) | Hoogte van voorbeeld. |
| [setHeight(int value)](#setHeight-int-) | Hoogte van voorbeeld. |
| [getResolution()](#getResolution--) | Afbeeldingsresolutie. |
| [setResolution(int value)](#setResolution-int-) | Afbeeldingsresolutie. |
| [getMode()](#getMode--) | Modus voor voorbeeldweergave. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de voorbeeldopties. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Haalt het volledige bestandspad van het voorbeelddocument op basis van paginanummer met gedefinieerde extensie. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory voor het maken of vrijgeven van de uitvoerpagina-voorbeeldstroom. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | De methode die de stroom instantiateert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
| previewMode | int | De voorbeeldmodus van Modus (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | De methode die de stroom instantiateert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
| previewMode | int | De voorbeeldmodus van Modus (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Paginanummers. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | De methode die de stroom instantiateert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
| previewMode | int | De voorbeeldmodus van Modus (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | De methode die de stroom instantiateert die wordt gebruikt om uitvoerpagina-gegevens te schrijven. |
| previewMode | int | De voorbeeldmodus van Modus (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Breedte van voorbeeld.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Breedte van voorbeeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hoogte van voorbeeld.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hoogte van voorbeeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Afbeeldingsresolutie.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Afbeeldingsresolutie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Modus voor voorbeeldweergave.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valideert de voorbeeldopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het bestandstype. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Haalt het volledige bestandspad van het voorbeelddocument op basis van paginanummer met gedefinieerde extensie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumber | int | Paginanummer van voorbeeld. |
| extensie | java.lang.String | Extensie van bestand. |

**Returns:**
java.lang.String - Het volledige bestandspad.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory voor het maken of vrijgeven van de uitvoerpagina-voorbeeldstroom.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
