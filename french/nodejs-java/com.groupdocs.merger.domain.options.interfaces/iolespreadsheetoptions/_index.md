---
title: "IOleSpreadsheetOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour les options d'importation du document intégré vers Spreadsheet via OLE."
type: docs
weight: 19
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

Interface pour les options d'importation du document intégré vers Spreadsheet via OLE.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | L'index de la ligne en haut à gauche. |
| [setRowIndex(int value)](#setRowIndex-int-) | L'index de la ligne en haut à gauche. |
| [getColumnIndex()](#getColumnIndex--) | L'index de la colonne en haut à gauche. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | L'index de la colonne en haut à gauche. |
| [getImageData()](#getImageData--) | Les données de l'image de l'objet Ole. |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


L'index de la ligne en haut à gauche.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


L'index de la ligne en haut à gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


L'index de la colonne en haut à gauche.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


L'index de la colonne en haut à gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Les données de l'image de l'objet Ole.

**Returns:**
byte[]
