---
title: "IOleDiagramOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour les options d'importation du document intégré vers Diagram via OLE."
type: docs
weight: 17
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Interface pour les options d'importation du document intégré vers Diagram via OLE.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getX()](#getX--) | La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [setX(int value)](#setX-int-) | La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [getY()](#getY--) | La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [setY(int value)](#setY-int-) | La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [getImageData()](#getImageData--) | Les données d'image de l'objet intégré. |
### getX() {#getX--}
```
public abstract int getX()
```


La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Les données d'image de l'objet intégré.

**Returns:**
byte[]
