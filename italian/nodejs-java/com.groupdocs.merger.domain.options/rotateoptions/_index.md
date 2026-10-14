---
title: "RotateOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per la rotazione della pagina."
type: docs
weight: 33
url: /it/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Fornisce opzioni per la rotazione della pagina.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMode()](#getMode--) | Ottiene la modalità per la rotazione (90, 180 o 270 gradi). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateMode | int | La modalità di rotazione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateMode | int | La modalità di rotazione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Numeri di pagina. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateMode | int | La modalità di rotazione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotateMode | int | La modalità di rotazione di Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### getMode() {#getMode--}
```
public final int getMode()
```


Ottiene la modalità per la rotazione (90, 180 o 270 gradi).

**Returns:**
int
