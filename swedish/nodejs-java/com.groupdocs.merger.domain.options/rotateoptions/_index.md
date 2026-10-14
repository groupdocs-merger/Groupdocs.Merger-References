---
title: "RotateOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för sidrotation."
type: docs
weight: 33
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Tillhandahåller alternativ för sidrotation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMode()](#getMode--) | Hämtar läget för rotation (90, 180 eller 270 grader). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateMode | int | Rotationsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateMode | int | Rotationsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Sidnummer. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateMode | int | Rotationsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateMode | int | Rotationsläget för Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |
| mode | int | Områdesläget. |

### getMode() {#getMode--}
```
public final int getMode()
```


Hämtar läget för rotation (90, 180 eller 270 grader).

**Returns:**
int
