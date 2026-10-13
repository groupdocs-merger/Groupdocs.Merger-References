---
title: "SplitOptions"
second_title: "GroupDocs.Merger för Java API-referens"
description: "Tillhandahåller alternativ för dokumentets siddelning."
type: docs
weight: 38
url: /sv/java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Tillhandahåller alternativ för dokumentets siddelning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMode()](#getMode--) | Hämtar läget för siduppdelning. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validerar uppdelningsalternativen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Hämtar hela filsökvägen för delat dokument efter index med fördefinierad filändelse. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory för att skapa eller släppa utdata sidförhandsgranskningsström. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumbers | int[] | Sidnummer. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |
| mode | int | Räckviddsläget. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan fördefinierad filändelse. |
| pageNumbers | int[] | Sidnummer. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan fördefinierad filändelse. |
| pageNumbers | int[] | Sidnummer. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan fördefinierad filändelse. |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan fördefinierad filändelse. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan fördefinierad filändelse. |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |
| mode | java.lang.Integer | Räckviddsläget. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filvägsformatet t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan fördefinierad filändelse. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |
| mode | int | Räckviddsläget. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |
| pageNumbers | int[] | Sidnummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |
| pageNumbers | int[] | Sidnummer. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |
| mode | java.lang.Integer | Räckviddsläget. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som skapar strömmen som används för att skriva utdata för delade data. |
| splitMode | int | Delningsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)). |
| startNumber | int | Startsidans nummer. |
| endNumber | int | Slutsidans nummer. |
| mode | int | Räckviddsläget. |

### getMode() {#getMode--}
```
public final int getMode()
```


Hämtar läget för siduppdelning.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Validerar uppdelningsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filtypen för klassen [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Hämtar hela filsökvägen för delat dokument efter index med fördefinierad filändelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för delat dokument. |
| filändelse | java.lang.String | Filens filändelse. |

**Returns:**
java.lang.String - Den fullständiga filsökvägen.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory för att skapa eller släppa utdata sidförhandsgranskningsström.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
