---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för dokumentets textuppdelning."
type: docs
weight: 39
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Tillhandahåller alternativ för dokumentets textuppdelning.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMode()](#getMode--) | Läge för textuppdelning. |
| [getLineNumbers()](#getLineNumbers--) | Radnummer för textuppdelning. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validerar uppdelningsalternativen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Hämtar den fullständiga filsökvägen för delat dokument efter index med definierad filändelse. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory för att skapa eller frigöra förhandsgranskningsström för utdata sida. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lineNumbers | int[] | Radnummer för textuppdelning. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | int | Läge för textuppdelning. |
| lineNumbers | int[] | Radnummer för textuppdelning. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filens sökvägsformat t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan definierad filändelse. |
| lineNumbers | int[] | Radnummer för textuppdelning. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePathFormat | java.lang.String | Filens sökvägsformat t.ex. 'c:/split\{0\}.doc' eller 'c:/split\{0\}.\{1\}' med redan definierad filändelse. |
| mode | int | Läge för textuppdelning. |
| lineNumbers | int[] | Radnummer för textuppdelning. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som instansierar strömmen som används för att skriva utdata split-data. |
| lineNumbers | int[] | Radnummer för textuppdelning. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Initierar en ny instans av klassen [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Metoden som instansierar strömmen som används för att skriva utdata split-data. |
| mode | int | Läge för textuppdelning. |
| lineNumbers | int[] | Radnummer för textuppdelning. |

### getMode() {#getMode--}
```
public final int getMode()
```


Läge för textuppdelning.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Radnummer för textuppdelning.

**Returns:**
int[]
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


Hämtar den fullständiga filsökvägen för delat dokument efter index med definierad filändelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för delat dokument. |
| filändelse | java.lang.String | Filändelse för filen. |

**Returns:**
java.lang.String - Den fullständiga filsökvägen.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory för att skapa eller frigöra förhandsgranskningsström för utdata sida.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
