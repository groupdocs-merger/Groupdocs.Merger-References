---
title: "MoveOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen zum Verschieben von Dokumentenseiten."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Bietet Optionen zum Verschieben von Dokumentenseiten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Initialisiert eine neue Instanz der [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Ermittelt oder legt die zu verschiebende Seitennummer fest. |
| [getNewPageNumber()](#getNewPageNumber--) | Ermittelt oder legt die neue Seitennummer fest. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Initialisiert eine neue Instanz der [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumberToMove | int | Die zu verschiebende Seitenzahl. |
| newPageNumber | int | Die neue Seitenzahl. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Ermittelt oder legt die zu verschiebende Seitennummer fest.

Wert: Die zu verschiebende Seitennummer.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Ermittelt oder legt die neue Seitennummer fest.

Wert: Die neue Seitennummer.

**Returns:**
int
