---
title: "PreviewOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Stellt Optionen für die Dokumentvorschau dar."
type: docs
weight: 29
url: /de/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Stellt Optionen für die Dokumentvorschau dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Vorschau-Breite. |
| [setWidth(int value)](#setWidth-int-) | Vorschau-Breite. |
| [getHeight()](#getHeight--) | Vorschau-Höhe. |
| [setHeight(int value)](#setHeight-int-) | Vorschau-Höhe. |
| [getResolution()](#getResolution--) | Bildauflösung. |
| [setResolution(int value)](#setResolution-int-) | Bildauflösung. |
| [getMode()](#getMode--) | Modus für die Vorschau. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Vorschaueinstellungen. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des Vorschau-Dokuments anhand der Seitenzahl mit definierter Erweiterung. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory zum Erstellen oder Freigeben des Ausgabeseiten‑Vorschau‑Streams. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | int | Der Vorschaumodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | int | Der Vorschaumodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Seitenzahlen. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | int | Der Vorschaumodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben von Ausgabeseitendaten verwendet wird. |
| previewMode | int | Der Vorschaumodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Vorschau-Breite.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Vorschau-Breite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Vorschau-Höhe.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Vorschau-Höhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Bildauflösung.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Bildauflösung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Modus für die Vorschau.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validiert die Vorschaueinstellungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Dateityp. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory zum Erstellen oder Freigeben des Ausgabeseiten‑Vorschau‑Streams.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
