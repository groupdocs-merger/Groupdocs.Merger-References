---
title: "SplitOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für das Aufteilen von Dokumentseiten."
type: docs
weight: 36
url: /de/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Bietet Optionen für das Aufteilen von Dokumentseiten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMode()](#getMode--) | Ermittelt den Modus für das Aufteilen von Seiten. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validiert die Aufteilungsoptionen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments nach Index mit vordefinierter Erweiterung. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory zum Erstellen oder Freigeben des Ausgabeseiten-Vorschau-Streams. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumbers | int[] | Seitenzahlen. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}' mit bereits vordefinierter Erweiterung. |
| pageNumbers | int[] | Seitenzahlen. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}' mit bereits vordefinierter Erweiterung. |
| pageNumbers | int[] | Seitenzahlen. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}' mit bereits vordefinierter Erweiterung. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}' mit bereits vordefinierter Erweiterung. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}' mit bereits vordefinierter Erweiterung. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | java.lang.Integer | Der Bereichsmodus. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePathFormat | java.lang.String | Das Dateipfadformat, z. B. 'c:/split\{0\}.doc' oder 'c:/split\{0\}.\{1\}' mit bereits vordefinierter Erweiterung. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| pageNumbers | int[] | Seitenzahlen. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| pageNumbers | int[] | Seitenzahlen. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | java.lang.Integer | Der Bereichsmodus. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Die Methode, die den Stream instanziiert, der zum Schreiben der ausgegebenen geteilten Daten verwendet wird. |
| splitMode | int | Der Aufteilungsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ermittelt den Modus für das Aufteilen von Seiten.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validiert die Aufteilungsoptionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Dateityp der Klasse [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Ermittelt den vollständigen Dateipfad des aufgeteilten Dokuments nach Index mit vordefinierter Erweiterung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Index des geteilten Dokuments. |
| Erweiterung | java.lang.String | Erweiterung der Datei. |

**Returns:**
java.lang.String - Der vollständige Dateipfad.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory zum Erstellen oder Freigeben des Ausgabeseiten-Vorschau-Streams.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
