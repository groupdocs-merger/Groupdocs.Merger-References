---
title: "RotateOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für die Seitenrotation."
type: docs
weight: 33
url: /de/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Bietet Optionen für die Seitenrotation.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse. |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMode()](#getMode--) | Ermittelt den Modus zum Drehen (90, 180 oder 270 Grad). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateMode | int | Der Rotationsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateMode | int | Der Rotationsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Seitenzahlen. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateMode | int | Der Rotationsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateMode | int | Der Rotationsmodus von Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ermittelt den Modus zum Drehen (90, 180 oder 270 Grad).

**Returns:**
int
