---
title: "OrientationOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'orientamento della pagina."
type: docs
weight: 23
url: /it/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Fornisce opzioni per l'orientamento della pagina.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getMode()](#getMode--) | Restituisce la modalità per l'orientamento della pagina. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientationMode | int | La modalità di orientamento di [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientationMode | int | La modalità di orientamento di [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | Numeri di pagina. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientationMode | int | La modalità di orientamento di [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Inizializza una nuova istanza della classe [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientationMode | int | La modalità di orientamento di [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | Il numero di pagina iniziale. |
| endNumber | int | Il numero di pagina finale. |
| mode | int | La modalità di intervallo. |

### getMode() {#getMode--}
```
public final int getMode()
```


Restituisce la modalità per l'orientamento della pagina.

**Returns:**
int
