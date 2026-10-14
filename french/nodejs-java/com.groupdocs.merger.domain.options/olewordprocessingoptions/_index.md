---
title: "OleWordProcessingOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour l'importation du document intégré dans Word processing via OLE."
type: docs
weight: 21
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Fournit des options pour l'importation du document intégré dans Word processing via OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Initialise une nouvelle instance de la classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Initialise une nouvelle instance de la classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Initialise une nouvelle instance de la classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLeft()](#getLeft--) | La coordonnée gauche de l'image de l'objet Ole. |
| [setLeft(int value)](#setLeft-int-) | La coordonnée gauche de l'image de l'objet Ole. |
| [getTop()](#getTop--) | La coordonnée supérieure de l'image de l'objet Ole. |
| [setTop(int value)](#setTop-int-) | La coordonnée supérieure de l'image de l'objet Ole. |
| [getWidth()](#getWidth--) | La largeur de l'image de l'objet Ole. |
| [setWidth(int value)](#setWidth-int-) | La largeur de l'image de l'objet Ole. |
| [getHeight()](#getHeight--) | La hauteur de l'image de l'objet Ole. |
| [setHeight(int value)](#setHeight-int-) | La hauteur de l'image de l'objet Ole. |
| [getImageData()](#getImageData--) | Les données de l'image de l'objet Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectData | byte[] | Les données de l'objet intégré. |
| imageData | byte[] | Les données d'image de l'objet intégré. |
| extension | java.lang.String | L'extension de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| imageData | byte[] | Les données d'image de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


La coordonnée gauche de l'image de l'objet Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


La coordonnée gauche de l'image de l'objet Ole.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


La coordonnée supérieure de l'image de l'objet Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


La coordonnée supérieure de l'image de l'objet Ole.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


La largeur de l'image de l'objet Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


La largeur de l'image de l'objet Ole.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


La hauteur de l'image de l'objet Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


La hauteur de l'image de l'objet Ole.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Les données de l'image de l'objet Ole.

**Returns:**
byte[]
