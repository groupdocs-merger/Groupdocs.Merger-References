---
title: "ImportDocumentOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour l'importation du document intégré."
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Fournit des options pour l'importation du document intégré.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]
 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]
 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]
 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]
 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Initialise une nouvelle instance de la classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Initialise une nouvelle instance de la classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getObjectData()](#getObjectData--) | Les données de l'objet intégré. |
| [getExtension()](#getExtension--) | L'extension de l'objet intégré. |
| [getPageNumber()](#getPageNumber--) | Le numéro de page pour l'insertion de l'objet intégré. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Obtient les données d'image de l'objet incorporé. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Initialise une nouvelle instance de la classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectData | byte[] | Les données de l'objet intégré. |
| extension | java.lang.String | L'extension de l'objet intégré. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Initialise une nouvelle instance de la classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |
| pageNumber | int | Le numéro de page pour ajouter l'objet incorporé. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Les données de l'objet intégré.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


L'extension de l'objet intégré.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Le numéro de page pour l'insertion de l'objet intégré.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Obtient les données d'image de l'objet incorporé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |

**Returns:**
byte[]
