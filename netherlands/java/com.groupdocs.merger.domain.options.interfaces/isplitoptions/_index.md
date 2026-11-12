---
title: "ISplitOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Interface voor de splitsingsopties."
type: docs
weight: 33
url: /nl/java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Interface voor de splitsingsopties.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Haalt de modus op voor het splitsen van pagina's. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valideert de splitopties. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Haalt het volledige bestandspad op van het gesplitste document op basis van de index met de gedefinieerde extensie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Delegate die de methode definieert om een uitvoer‑splitstream te maken. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Haalt de modus op voor het splitsen van pagina's.

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
