---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Biedt opties voor het splitsen van documenttekst."
type: docs
weight: 41
url: /nl/java/com.groupdocs.merger.domain.options/textsplitoptions/
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
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse. |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse. |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse. |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Modus voor tekstdeling. |
| [getLineNumbers()](#getLineNumbers--) | Regelnummers voor tekstdeling. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitopties. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Haalt het volledige bestandspad op van het gesplitste document op basis van de index met de gedefinieerde extensie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory om een uitvoer-paginavoorbeeldstroom te maken of vrij te geven. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lineNumbers | int[] | Regelnummers voor tekstdeling. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| modus | int | Modus voor tekstdeling. |
| lineNumbers | int[] | Regelnummers voor tekstdeling. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds gedefinieerde extensie. |
| lineNumbers | int[] | Regelnummers voor tekstdeling. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds gedefinieerde extensie. |
| modus | int | Modus voor tekstdeling. |
| lineNumbers | int[] | Regelnummers voor tekstdeling. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stroom instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| lineNumbers | int[] | Regelnummers voor tekstdeling. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Initialiseert een nieuw exemplaar van de [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stroom instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| modus | int | Modus voor tekstdeling. |
| lineNumbers | int[] | Regelnummers voor tekstdeling. |

### getMode() {#getMode--}
```
public final int getMode()
```


Modus voor tekstdeling.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Regelnummers voor tekstdeling.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Valideert de splitopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het bestandstype van de klasse [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Haalt het volledige bestandspad op van het gesplitste document op basis van de index met de gedefinieerde extensie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het gesplitste document. |
| extensie | java.lang.String | Extensie van bestand. |

**Returns:**
java.lang.String - Het volledige bestandspad.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory om een uitvoer-paginavoorbeeldstroom te maken of vrij te geven.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
