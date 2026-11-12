---
title: "OrientationOptions"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Biedt opties voor de paginarichting."
type: docs
weight: 23
url: /nl/java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Biedt opties voor de paginarichting.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getMode()](#getMode--) | Haalt de modus voor de paginageoriëntatie op. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| pageNumbers | int[] | Paginanummers. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

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


Initialiseert een nieuw exemplaar van de klasse [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientationMode | int | De oriëntatiemodus van [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Het startpaginanummer. |
| endNumber | int | Het eindpaginanummer. |
| modus | int | De bereikmodus. |

### getMode() {#getMode--}
```
public final int getMode()
```


Haalt de modus voor de paginageoriëntatie op.

**Returns:**
int
