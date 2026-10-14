---
title: "PageJoinOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für das Zusammenführen von Dokumenten."
type: docs
weight: 25
url: /de/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Bietet Optionen für das Zusammenführen von Dokumenten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Der Typ der zu verbindenden Datei. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumbers | int[] | Seitenzahlen. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |
| pageNumbers | int[] | Seitenzahlen. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Der Typ der zu verbindenden Datei. |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### getType() {#getType--}
```
public final FileType getType()
```


Der Typ der zu verbindenden Datei.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
