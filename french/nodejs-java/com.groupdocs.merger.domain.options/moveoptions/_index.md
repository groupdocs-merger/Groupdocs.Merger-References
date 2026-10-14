---
title: "MoveOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour déplacer la page du document."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

Fournit des options pour déplacer la page du document.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | Initialise une nouvelle instance de la classe [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | Obtient ou définit le numéro de page à déplacer. |
| [getNewPageNumber()](#getNewPageNumber--) | Obtient ou définit le nouveau numéro de page. |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


Initialise une nouvelle instance de la classe [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumberToMove | int | Le numéro de page à déplacer. |
| newPageNumber | int | Le nouveau numéro de page. |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


Obtient ou définit le numéro de page à déplacer.

Valeur : le numéro de page à déplacer.

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


Obtient ou définit le nouveau numéro de page.

Valeur : le nouveau numéro de page.

**Returns:**
int
