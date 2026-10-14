---
title: "MoveOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para mover la página del documento."
type: docs
weight: 17
url: /es/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Proporciona opciones para mover la página del documento.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Inicializa una nueva instancia de la clase [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Obtiene o establece el número de página a mover. |
| [getNewPageNumber()](#getNewPageNumber--) | Obtiene o establece el nuevo número de página. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Inicializa una nueva instancia de la clase [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumberToMove | int | El número de página a mover. |
| newPageNumber | int | El nuevo número de página. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Obtiene o establece el número de página a mover.

Valor: El número de página a mover.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Obtiene o establece el nuevo número de página.

Valor: El nuevo número de página.

**Returns:**
int
