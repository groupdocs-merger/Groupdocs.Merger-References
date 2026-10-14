---
title: "OrientationOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour l'orientation des pages."
type: docs
weight: 23
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Fournit des options pour l'orientation des pages.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMode()](#getMode--) | Obtient le mode d'orientation de la page. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| orientationMode | int | Le mode d'orientation de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| orientationMode | int | Le mode d'orientation de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | Numéros de page. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| orientationMode | int | Le mode d'orientation de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| orientationMode | int | Le mode d'orientation de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtient le mode d'orientation de la page.

**Returns:**
int
