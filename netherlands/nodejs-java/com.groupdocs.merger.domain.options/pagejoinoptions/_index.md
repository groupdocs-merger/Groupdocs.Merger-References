---
title: "PageJoinOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het samenvoegen van documenten."
type: docs
weight: 25
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Biedt opties voor het samenvoegen van documenten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getType()](#getType--) | Het type van het bestand dat moet worden samengevoegd. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumbers | int[] | Paginanummers. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand dat moet worden samengevoegd. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand dat moet worden samengevoegd. |
| pageNumbers | int[] | Paginanummers. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand dat moet worden samengevoegd. |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het type van het bestand dat moet worden samengevoegd. |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### getType() {#getType--}
```
public final FileType getType()
```


Het type van het bestand dat moet worden samengevoegd.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
