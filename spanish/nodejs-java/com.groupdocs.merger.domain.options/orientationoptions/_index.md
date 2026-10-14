---
title: "OrientationOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la orientación de la página."
type: docs
weight: 23
url: /es/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Proporciona opciones para la orientación de la página.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMode()](#getMode--) | Obtiene el modo para la orientación de la página. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orientationMode | int | El modo de orientación de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orientationMode | int | El modo de orientación de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| pageNumbers | int[] | Números de página. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orientationMode | int | El modo de orientación de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orientationMode | int | El modo de orientación de [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode). |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtiene el modo para la orientación de la página.

**Returns:**
int
