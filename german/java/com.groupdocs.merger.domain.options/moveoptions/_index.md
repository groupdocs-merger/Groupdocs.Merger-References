---
title: "MoveOptions"
second_title: "GroupDocs.Merger für Java API-Referenz"
description: "Bietet Optionen zum Verschieben von Dokumentseiten."
type: docs
weight: 17
url: /de/java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Bietet Optionen zum Verschieben von Dokumentseiten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Initialisiert eine neue Instanz der [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Liest oder setzt die zu verschiebende Seitennummer. |
| [getNewPageNumber()](#getNewPageNumber--) | Liest oder setzt die neue Seitennummer. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Initialisiert eine neue Instanz der [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageNumberToMove | int | Die zu verschiebende Seitennummer. |
| newPageNumber | int | Die neue Seitenzahl. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Liest oder setzt die zu verschiebende Seitennummer.

Wert: Die zu verschiebende Seitennummer.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Liest oder setzt die neue Seitennummer.

Wert: Die neue Seitennummer.

**Returns:**
int
