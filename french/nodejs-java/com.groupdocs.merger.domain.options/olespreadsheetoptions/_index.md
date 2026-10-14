---
title: "OleSpreadsheetOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour l'importation du document intégré dans Spreadsheet via OLE."
type: docs
weight: 20
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

Fournit des options pour l'importation du document intégré dans Spreadsheet via OLE.

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | Initialise une nouvelle instance de la classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | Initialise une nouvelle instance de la classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | Initialise une nouvelle instance de la classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | L'index de la ligne en haut à gauche. |
| [setRowIndex(int value)](#setRowIndex-int-) | L'index de la ligne en haut à gauche. |
| [getColumnIndex()](#getColumnIndex--) | L'index de la colonne en haut à gauche. |
| [setColumnIndex(int value)](#setColumnIndex-int-) | L'index de la colonne en haut à gauche. |
| [getWidth()](#getWidth--) | La largeur de l'image de l'objet Ole. |
| [setWidth(int value)](#setWidth-int-) | La largeur de l'image de l'objet Ole. |
| [getHeight()](#getHeight--) | La hauteur de l'image de l'objet Ole. |
| [setHeight(int value)](#setHeight-int-) | La hauteur de l'image de l'objet Ole. |
| [getImageData()](#getImageData--) | Les données de l'image de l'objet Ole. |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectData | byte[] | Les données de l'objet intégré. |
| imageData | byte[] | Les données d'image de l'objet intégré. |
| extension | java.lang.String | L'extension de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| imageData | byte[] | Les données d'image de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


Initialise une nouvelle instance de la classe [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


L'index de la ligne en haut à gauche.

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


L'index de la ligne en haut à gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


L'index de la colonne en haut à gauche.

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


L'index de la colonne en haut à gauche.

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
