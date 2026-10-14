---
title: "WordJoinOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Word-sammanslagningsalternativen."
type: docs
weight: 43
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Word-sammanslagningsalternativen.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMode()](#getMode--) | Word-anslutningsläget. |
| [setMode(int value)](#setMode-int-) | Word-anslutningsläget. |
| [getCompliance()](#getCompliance--) | Kompatibilitetsläge för Word Ooxml-formatet |
| [setCompliance(int value)](#setCompliance-int-) | Kompatibilitetsläge för Word Ooxml-formatet |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumbers | int[] | Sidnummer. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |
| mode | int | Områdesläget. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska slås samman. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska slås samman. |
| pageNumbers | int[] | Sidnummer. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska slås samman. |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Typen av filen som ska slås samman. |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |
| mode | int | Områdesläget. |

### getMode() {#getMode--}
```
public final int getMode()
```


Word-anslutningsläget.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Word-anslutningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Kompatibilitetsläge för Word Ooxml-formatet

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Kompatibilitetsläge för Word Ooxml-formatet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

