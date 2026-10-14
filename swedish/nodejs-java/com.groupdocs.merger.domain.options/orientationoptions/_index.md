---
title: "OrientationOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för sidorientering."
type: docs
weight: 23
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Tillhandahåller alternativ för sidorientering.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getMode()](#getMode--) | Hämtar läget för sidorienteringen. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientationMode | int | Orienteringsläget för [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientationMode | int | Orienteringsläget för [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | Sidnummer. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientationMode | int | Orienteringsläget för [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Initierar en ny instans av klassen [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientationMode | int | Orienteringsläget för [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Startsidnummer. |
| endNumber | int | Slutsidnummer. |
| mode | int | Områdesläget. |

### getMode() {#getMode--}
```
public final int getMode()
```


Hämtar läget för sidorienteringen.

**Returns:**
int
