---
title: "IOleWordProcessingOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour les options d'importation du document intégré vers Word processing via OLE."
type: docs
weight: 20
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Interface pour les options d'importation du document intégré vers Word processing via OLE.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLeft()](#getLeft--) | La coordonnée gauche de l'image de l'objet Ole. |
| [setLeft(int value)](#setLeft-int-) | La coordonnée gauche de l'image de l'objet Ole. |
| [getTop()](#getTop--) | La coordonnée supérieure de l'image de l'objet Ole. |
| [setTop(int value)](#setTop-int-) | La coordonnée supérieure de l'image de l'objet Ole. |
| [getImageData()](#getImageData--) | Les données de l'image de l'objet Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


La coordonnée gauche de l'image de l'objet Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


La coordonnée gauche de l'image de l'objet Ole.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


La coordonnée supérieure de l'image de l'objet Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


La coordonnée supérieure de l'image de l'objet Ole.

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
