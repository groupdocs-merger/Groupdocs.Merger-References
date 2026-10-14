---
title: "RotateOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour la rotation de la page."
type: docs
weight: 33
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Fournit des options pour la rotation de la page.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMode()](#getMode--) | Obtient le mode de rotation (90, 180 ou 270 degrés). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateMode | int | Le mode de rotation du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateMode | int | Le mode de rotation du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Numéros de page. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateMode | int | Le mode de rotation du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Initialise une nouvelle instance de la classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateMode | int | Le mode de rotation du Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Le numéro de page de début. |
| endNumber | int | Le numéro de page de fin. |
| mode | int | Le mode de plage. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtient le mode de rotation (90, 180 ou 270 degrés).

**Returns:**
int
