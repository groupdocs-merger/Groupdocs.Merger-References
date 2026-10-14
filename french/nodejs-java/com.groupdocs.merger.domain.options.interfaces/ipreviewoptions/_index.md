---
title: "IPreviewOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour les options d'aperçu."
type: docs
weight: 28
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Interface pour les options d'aperçu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Largeur de l'aperçu. |
| [setWidth(int value)](#setWidth-int-) | Largeur de l'aperçu. |
| [getHeight()](#getHeight--) | Hauteur de l'aperçu. |
| [setHeight(int value)](#setHeight-int-) | Hauteur de l'aperçu. |
| [getResolution()](#getResolution--) | Résolution de l'image. |
| [setResolution(int value)](#setResolution-int-) | Résolution de l'image. |
| [getMode()](#getMode--) | Obtient le mode d'aperçu. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valide les options de division. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Obtient le chemin complet du fichier du document prévisualisé par numéro de page avec l'extension définie. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Délégué qui définit la méthode pour créer le flux de prévisualisation de la page de sortie. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Largeur de l'aperçu.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Largeur de l'aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Hauteur de l'aperçu.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Hauteur de l'aperçu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Résolution de l'image.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Résolution de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Obtient le mode d'aperçu.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valide les options de division.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type de fichier de la classe [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Obtient le chemin complet du fichier du document prévisualisé par numéro de page avec l'extension définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | int | Numéro de page de l'aperçu. |
| extension | java.lang.String | Extension du fichier. |

**Returns:**
java.lang.String - Le chemin complet du fichier.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Délégué qui définit la méthode pour créer le flux de prévisualisation de la page de sortie.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
