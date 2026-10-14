---
title: "TextSplitOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het splitsen van documenttekst."
type: docs
weight: 39
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Biedt opties voor het splitsen van documenttekst.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Modus voor het splitsen van tekst. |
| [getLineNumbers()](#getLineNumbers--) | Regelnummers voor het splitsen van tekst. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitsopties. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Haalt het volledige bestandspad op van het gesplitste document op basis van de index met gedefinieerde extensie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory voor het maken of vrijgeven van een uitvoerpagina‑voorbeeldstroom. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lineNumbers | int[] | Regelnummers voor het splitsen van tekst. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mode | int | Modus voor het splitsen van tekst. |
| lineNumbers | int[] | Regelnummers voor het splitsen van tekst. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat, bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds gedefinieerde extensie. |
| lineNumbers | int[] | Regelnummers voor het splitsen van tekst. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat, bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds gedefinieerde extensie. |
| mode | int | Modus voor het splitsen van tekst. |
| lineNumbers | int[] | Regelnummers voor het splitsen van tekst. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| lineNumbers | int[] | Regelnummers voor het splitsen van tekst. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| mode | int | Modus voor het splitsen van tekst. |
| lineNumbers | int[] | Regelnummers voor het splitsen van tekst. |

### getMode() {#getMode--}
```
public final int getMode()
```


Modus voor het splitsen van tekst.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Regelnummers voor het splitsen van tekst.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valideert de splitsopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het bestandstype van de [FileType](../../com.groupdocs.merger.domain/filetype) klasse. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Haalt het volledige bestandspad op van het gesplitste document op basis van de index met gedefinieerde extensie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van gesplitst document. |
| extensie | java.lang.String | Extensie van bestand. |

**Returns:**
java.lang.String - Het volledige bestandspad.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory voor het maken of vrijgeven van een uitvoerpagina‑voorbeeldstroom.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
