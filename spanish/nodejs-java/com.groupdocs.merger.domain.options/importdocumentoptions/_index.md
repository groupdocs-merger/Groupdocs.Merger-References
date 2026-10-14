---
title: "ImportDocumentOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para la importación del documento incrustado."
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Proporciona opciones para la importación del documento incrustado.

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
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Inicializa una nueva instancia de la clase [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Inicializa una nueva instancia de la clase [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getObjectData()](#getObjectData--) | Los datos del objeto incrustado. |
| [getExtension()](#getExtension--) | La extensión del objeto incrustado. |
| [getPageNumber()](#getPageNumber--) | El número de página para insertar el objeto incrustado. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Obtiene los datos de imagen del objeto incrustado. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Inicializa una nueva instancia de la clase [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectData | byte[] | Los datos del objeto incrustado. |
| extensión | java.lang.String | La extensión del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Inicializa una nueva instancia de la clase [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |
| pageNumber | int | El número de página para agregar el objeto incrustado. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Los datos del objeto incrustado.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


La extensión del objeto incrustado.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


El número de página para insertar el objeto incrustado.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Obtiene los datos de imagen del objeto incrustado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |

**Returns:**
byte[]
