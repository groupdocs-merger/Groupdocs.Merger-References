---
title: "ITextSplitOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Interface voor de tekstsplitsingsopties."
type: docs
weight: 35
url: /nl/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Interface voor de tekstsplitsingsopties.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Regelnummers voor het splitsen van tekst. |
| [getMode()](#getMode--) | Modus voor het splitsen van tekst. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitsopties. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Haalt het volledige bestandspad op van het gesplitste document op basis van de index met gedefinieerde extensie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate die methode definieert om een uitvoer-splitstream te maken. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Regelnummers voor het splitsen van tekst.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Modus voor het splitsen van tekst.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valideert de splitsopties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het bestandstype van de [FileType](../../com.groupdocs.merger.domain/filetype) klasse. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Delegate die methode definieert om een uitvoer-splitstream te maken.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
