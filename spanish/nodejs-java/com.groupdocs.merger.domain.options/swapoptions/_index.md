---
title: "SwapOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para intercambiar páginas del documento."
type: docs
weight: 37
url: /es/nodejs-java/com.groupdocs.merger.domain.options/swapoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions)
```
public class SwapOptions implements ISwapOptions
```

Proporciona opciones para intercambiar páginas del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SwapOptions(int firstPageNumber, int secondPageNumber)](#SwapOptions-int-int-) | Inicializa una nueva instancia de la clase [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFirstPageNumber()](#getFirstPageNumber--) | Primer número de página a intercambiar. |
| [getSecondPageNumber()](#getSecondPageNumber--) | Segundo número de página a intercambiar. |
### SwapOptions(int firstPageNumber, int secondPageNumber) {#SwapOptions-int-int-}
```
public SwapOptions(int firstPageNumber, int secondPageNumber)
```


Inicializa una nueva instancia de la clase [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstPageNumber | int | El primer número de página. |
| secondPageNumber | int | El número de la segunda página. |

### getFirstPageNumber() {#getFirstPageNumber--}
```
public final int getFirstPageNumber()
```


Primer número de página a intercambiar.

**Returns:**
int
### getSecondPageNumber() {#getSecondPageNumber--}
```
public final int getSecondPageNumber()
```


Segundo número de página a intercambiar.

**Returns:**
int
