---
title: "IPreviewOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor de previewopties."
type: docs
weight: 28
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Interface voor de previewopties.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Breedte van voorbeeld. |
| [setWidth(int value)](#setWidth-int-) | Breedte van voorbeeld. |
| [getHeight()](#getHeight--) | Hoogte van voorbeeld. |
| [setHeight(int value)](#setHeight-int-) | Hoogte van voorbeeld. |
| [getResolution()](#getResolution--) | Afbeeldingsresolutie. |
| [setResolution(int value)](#setResolution-int-) | Afbeeldingsresolutie. |
| [getMode()](#getMode--) | Haalt de modus voor voorbeeld op. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitsopties. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Haalt het volledige bestandspad van het voorbeelddocument op basis van paginanummer met gedefinieerde extensie. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegate die de methode definieert om een uitvoerpagina-voorbeeldstroom te maken. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Breedte van voorbeeld.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Breedte van voorbeeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Hoogte van voorbeeld.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Hoogte van voorbeeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Afbeeldingsresolutie.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Afbeeldingsresolutie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Haalt de modus voor voorbeeld op.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valideert de splitsopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het bestandstype van de [FileType](../../com.groupdocs.merger.domain/filetype) klasse. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
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
public abstract PageStreamFactory getPageStreamFactory()
```


Delegate die de methode definieert om een uitvoerpagina-voorbeeldstroom te maken.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
