---
title: "MoveOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het verplaatsen van een documentpagina."
type: docs
weight: 17
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Biedt opties voor het verplaatsen van een documentpagina.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Initialiseert een nieuw exemplaar van de klasse [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Haalt op of stelt het paginanummer in om te verplaatsen. |
| [getNewPageNumber()](#getNewPageNumber--) | Haalt op of stelt het nieuwe paginanummer in. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Initialiseert een nieuw exemplaar van de klasse [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pageNumberToMove | int | Het paginanummer om te verplaatsen. |
| newPageNumber | int | Het nieuwe paginanummer. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Haalt op of stelt het paginanummer in om te verplaatsen.

Waarde: Het paginanummer om te verplaatsen.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Haalt op of stelt het nieuwe paginanummer in.

Waarde: Het nieuwe paginanummer.

**Returns:**
int
