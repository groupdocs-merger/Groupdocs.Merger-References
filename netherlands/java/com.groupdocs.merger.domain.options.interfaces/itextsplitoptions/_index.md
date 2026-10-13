---
title: "ITextSplitOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Interface voor de opties voor het splitsen van tekst."
type: docs
weight: 35
url: /nl/java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Interface voor de opties voor het splitsen van tekst.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Regelnummers voor tekstdeling. |
| [getMode()](#getMode--) | Modus voor tekstdeling. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitopties. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Haalt het volledige bestandspad op van het gesplitste document op basis van de index met de gedefinieerde extensie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate die de methode definieert om een uitvoer‑splitstream te maken. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Regelnummers voor tekstdeling.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Modus voor tekstdeling.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valideert de splitopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het bestandstype van de klasse [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegate die de methode definieert om een uitvoer‑splitstream te maken.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
