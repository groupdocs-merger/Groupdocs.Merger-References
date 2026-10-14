---
title: "OrientationOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor de paginariëntatie."
type: docs
weight: 23
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Biedt opties voor de paginariëntatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse. |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Haalt de modus voor de pagina‑oriëntatie op. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| pageNumbers | int[] | Paginanummers. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Initialiseert een nieuw exemplaar van de [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| mode | int | De bereikmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Haalt de modus voor de pagina‑oriëntatie op.

**Returns:**
int
