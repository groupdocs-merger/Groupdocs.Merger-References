---
title: "SplitOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het splitsen van documentpagina's."
type: docs
weight: 36
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Biedt opties voor het splitsen van documentpagina's.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Haalt de modus op voor paginaverdeling. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitsopties. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Haalt het volledige bestandspad op van het gesplitste document op basis van de index met vooraf gedefinieerde extensie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory voor het maken of vrijgeven van een uitvoerpagina‑voorbeeldstroom. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumbers | int[] | Paginanummers. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds vooraf gedefinieerde extensie. |
| pageNumbers | int[] | Paginanummers. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds vooraf gedefinieerde extensie. |
| pageNumbers | int[] | Paginanummers. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds vooraf gedefinieerde extensie. |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds vooraf gedefinieerde extensie. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds vooraf gedefinieerde extensie. |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | java.lang.Integer | De bereikmodus. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePathFormat | java.lang.String | Het bestandspadformaat bijv. 'c:/split\{0\}.doc' of 'c:/split\{0\}.\{1\}' met reeds vooraf gedefinieerde extensie. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| pageNumbers | int[] | Paginanummers. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| pageNumbers | int[] | Paginanummers. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | java.lang.Integer | De bereikmodus. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | De methode die de stream instantiateert die wordt gebruikt om gesplitste uitvoergegevens te schrijven. |
| splitMode | int | De splitsingsmodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Haalt de modus op voor paginaverdeling.

**Returns:**
int
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


Haalt het volledige bestandspad op van het gesplitste document op basis van de index met vooraf gedefinieerde extensie.

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
