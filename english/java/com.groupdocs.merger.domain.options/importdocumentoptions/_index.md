---
title: ImportDocumentOptions
second_title: GroupDocs.Merger for Java API Reference
description: Provides options for the embedded document import.
type: docs
weight: 14
url: /java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Provides options for the embedded document import.

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
## Constructors

| Constructor | Description |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Initializes a new instance of the [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) class. |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Initializes a new instance of the [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectData()](#getObjectData--) | The data of the embedded object. |
| [getExtension()](#getExtension--) | The extension of the embedded object. |
| [getPageNumber()](#getPageNumber--) | The page number for inserting of the embedded object. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Gets image data of the embedded object. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Initializes a new instance of the [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectData | byte[] | The data of the embedded object. |
| extension | java.lang.String | The extension of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Initializes a new instance of the [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |
| pageNumber | int | The page number for adding embedded object. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


The data of the embedded object.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


The extension of the embedded object.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


The page number for inserting of the embedded object.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Gets image data of the embedded object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |

**Returns:**
byte[]
