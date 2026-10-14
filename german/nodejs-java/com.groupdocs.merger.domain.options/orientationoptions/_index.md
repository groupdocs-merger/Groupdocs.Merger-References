---
title: "OrientationOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für die Seitenausrichtung."
type: docs
weight: 23
url: /de/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Bietet Optionen für die Seitenausrichtung.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse. |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMode()](#getMode--) | Ermittelt den Modus für die Seitenausrichtung. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientationMode | int | Der Ausrichtungsmodus von [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientationMode | int | Der Ausrichtungsmodus von [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| pageNumbers | int[] | Seitenzahlen. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientationMode | int | Der Ausrichtungsmodus von [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Initialisiert eine neue Instanz der [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| orientationMode | int | Der Ausrichtungsmodus von [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Die Startseitennummer. |
| endNumber | int | Die Endseitennummer. |
| mode | int | Der Bereichsmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ermittelt den Modus für die Seitenausrichtung.

**Returns:**
int
