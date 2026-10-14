---
title: "WordJoinOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Die Word‑Zusammenführungsoptionen."
type: docs
weight: 43
url: /de/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Die Word‑Zusammenführungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMode()](#getMode--) | Der Word-Zusammenführungsmodus. |
| [setMode(int value)](#setMode-int-) | Der Word-Zusammenführungsmodus. |
| [getCompliance()](#getCompliance--) | Kompatibilitätsmodus für das Word-Ooxml-Format |
| [setCompliance(int value)](#setCompliance-int-) | Kompatibilitätsmodus für das Word-Ooxml-Format |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumbers | int[] | Seitenzahlen. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |
| pageNumbers | int[] | Seitenzahlen. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Der Word-Zusammenführungsmodus.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Der Word-Zusammenführungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Kompatibilitätsmodus für das Word-Ooxml-Format

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Kompatibilitätsmodus für das Word-Ooxml-Format

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

