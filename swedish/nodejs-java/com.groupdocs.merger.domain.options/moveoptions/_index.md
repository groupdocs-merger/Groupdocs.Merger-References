---
title: "MoveOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för att flytta dokumentsida."
type: docs
weight: 17
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Tillhandahåller alternativ för att flytta dokumentsida.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Initierar en ny instans av klassen [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Hämtar eller anger sidnumret att flytta. |
| [getNewPageNumber()](#getNewPageNumber--) | Hämtar eller anger det nya sidnumret. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Initierar en ny instans av klassen [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageNumberToMove | int | Sidnumret att flytta. |
| newPageNumber | int | Det nya sidnumret. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Hämtar eller anger sidnumret att flytta.

Värde: Sidnumret att flytta.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Hämtar eller anger det nya sidnumret.

Värde: Det nya sidnumret.

**Returns:**
int
