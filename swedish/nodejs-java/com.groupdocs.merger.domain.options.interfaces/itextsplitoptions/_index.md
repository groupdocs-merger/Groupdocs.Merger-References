---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Gränssnitt för textdelningsalternativen."
type: docs
weight: 35
url: /sv/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Gränssnitt för textdelningsalternativen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Radnummer för textuppdelning. |
| [getMode()](#getMode--) | Läge för textuppdelning. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Validerar uppdelningsalternativen. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Hämtar den fullständiga filsökvägen för delat dokument efter index med definierad filändelse. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegat som definierar metod för att skapa utdata-splitström. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Radnummer för textuppdelning.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Läge för textuppdelning.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Validerar uppdelningsalternativen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Filtypen för klassen [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegat som definierar metod för att skapa utdata-splitström.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
