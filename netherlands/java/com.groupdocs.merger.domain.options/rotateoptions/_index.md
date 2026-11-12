---
title: "RotateOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Biedt opties voor het roteren van pagina's."
type: docs
weight: 35
url: /nl/java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Biedt opties voor het roteren van pagina's.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse. |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Haalt de modus op voor roteren (90, 180 of 270 graden). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateMode | int | De rotatiemodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateMode | int | De rotatiemodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Paginanummers. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateMode | int | De rotatiemodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateMode | int | De rotatiemodus van Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| modus | int | De bereikmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Haalt de modus op voor roteren (90, 180 of 270 graden).

**Returns:**
int
