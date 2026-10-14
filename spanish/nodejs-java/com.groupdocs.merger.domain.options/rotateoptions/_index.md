---
title: "RotateOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la rotación de la página."
type: docs
weight: 33
url: /es/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Proporciona opciones para la rotación de la página.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getMode()](#getMode--) | Obtiene el modo de rotación (90, 180 o 270 grados). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateMode | int | El modo de rotación del Modo (\\#getMode.getMode/\\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateMode | int | El modo de rotación del Modo (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Números de página. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateMode | int | El modo de rotación del Modo (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Inicializa una nueva instancia de la clase [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateMode | int | El modo de rotación del Modo (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | El número de página inicial. |
| endNumber | int | El número de página final. |
| mode | int | El modo de rango. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtiene el modo de rotación (90, 180 o 270 grados).

**Returns:**
int
