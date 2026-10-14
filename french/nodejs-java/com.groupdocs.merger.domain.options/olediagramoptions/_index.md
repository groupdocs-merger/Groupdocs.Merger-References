---
title: "OleDiagramOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour l'importation du document intégré dans Diagram via OLE."
type: docs
weight: 18
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Fournit des options pour l'importation du document intégré dans Diagram via OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Initialise une nouvelle instance de la classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Initialise une nouvelle instance de la classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Initialise une nouvelle instance de la classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getX()](#getX--) | La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [setX(int value)](#setX-int-) | La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [getY()](#getY--) | La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [setY(int value)](#setY-int-) | La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page. |
| [getWidth()](#getWidth--) | La largeur de la forme de l'objet intégré en pouces. |
| [setWidth(int value)](#setWidth-int-) | La largeur de la forme de l'objet intégré en pouces. |
| [getHeight()](#getHeight--) | La hauteur de la forme de l'objet intégré en pouces. |
| [setHeight(int value)](#setHeight-int-) | La hauteur de la forme de l'objet intégré en pouces. |
| [getImageData()](#getImageData--) | Les données d'image de l'objet intégré. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectData | byte[] | Les données de l'objet intégré. |
| imageData | byte[] | Les données d'image de l'objet intégré. |
| extension | java.lang.String | L'extension de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| imageData | byte[] | Les données d'image de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### getX() {#getX--}
```
public final int getX()
```


La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


La coordonnée X du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


La coordonnée Y du point d'ancrage de la forme de l'objet intégré (centre de rotation) par rapport à la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


La largeur de la forme de l'objet intégré en pouces.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


La largeur de la forme de l'objet intégré en pouces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


La hauteur de la forme de l'objet intégré en pouces.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


La hauteur de la forme de l'objet intégré en pouces.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Les données d'image de l'objet intégré.

**Returns:**
byte[]
