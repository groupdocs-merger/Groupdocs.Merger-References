---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Schnittstelle für die Vorschauoptionen."
type: docs
weight: 28
url: /de/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Schnittstelle für die Vorschauoptionen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Vorschau-Breite. |
| [setWidth(int value)](#setWidth-int-) | Vorschau-Breite. |
| [getHeight()](#getHeight--) | Vorschau-Höhe. |
| [setHeight(int value)](#setHeight-int-) | Vorschau-Höhe. |
| [getResolution()](#getResolution--) | Bildauflösung. |
| [setResolution(int value)](#setResolution-int-) | Bildauflösung. |
| [getMode()](#getMode--) | Ermittelt den Modus für die Vorschau. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Aufteilungsoptionen. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des Vorschau-Dokuments anhand der Seitenzahl mit definierter Erweiterung. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Delegat, der die Methode zum Erzeugen eines Ausgabeseiten-Vorschau-Streams definiert. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Vorschau-Breite.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Vorschau-Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Vorschau-Höhe.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Vorschau-Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Bildauflösung.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Bildauflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Ermittelt den Modus für die Vorschau.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Validiert die Aufteilungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Dateityp der Klasse [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Ermittelt den vollständigen Dateipfad des Vorschau-Dokuments anhand der Seitenzahl mit definierter Erweiterung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumber | int | Seitenzahl der Vorschau. |
| Erweiterung | java.lang.String | Erweiterung der Datei. |

**Returns:**
java.lang.String - Der vollständige Dateipfad.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Delegat, der die Methode zum Erzeugen eines Ausgabeseiten-Vorschau-Streams definiert.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
