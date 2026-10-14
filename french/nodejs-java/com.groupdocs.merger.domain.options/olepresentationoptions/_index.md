---
title: "OlePresentationOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour l'importation du document intégré dans Presentation via OLE."
type: docs
weight: 19
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Fournit des options pour l'importation du document intégré dans Presentation via OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Initialise une nouvelle instance de la classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Initialise une nouvelle instance de la classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getX()](#getX--) | La coordonnée X du cadre d'objet intégré. |
| [setX(int value)](#setX-int-) | La coordonnée X du cadre d'objet intégré. |
| [getY()](#getY--) | La coordonnée Y du cadre d'objet intégré. |
| [setY(int value)](#setY-int-) | La coordonnée Y du cadre d'objet intégré. |
| [getWidth()](#getWidth--) | La largeur du cadre de l'objet incorporé. |
| [setWidth(int value)](#setWidth-int-) | La largeur du cadre de l'objet incorporé. |
| [getHeight()](#getHeight--) | La hauteur du cadre de l'objet incorporé. |
| [setHeight(int value)](#setHeight-int-) | La hauteur du cadre de l'objet incorporé. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Initialise une nouvelle instance de la classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectData | byte[] | Les données de l'objet intégré. |
| extension | java.lang.String | L'extension de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Initialise une nouvelle instance de la classe [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### getX() {#getX--}
```
public final int getX()
```


La coordonnée X du cadre d'objet intégré.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


La coordonnée X du cadre d'objet intégré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


La coordonnée Y du cadre d'objet intégré.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


La coordonnée Y du cadre d'objet intégré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


La largeur du cadre de l'objet incorporé.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


La largeur du cadre de l'objet incorporé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


La hauteur du cadre de l'objet incorporé.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


La hauteur du cadre de l'objet incorporé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

