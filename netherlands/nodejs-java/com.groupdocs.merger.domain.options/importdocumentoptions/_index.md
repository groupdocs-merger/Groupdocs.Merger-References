---
title: "ImportDocumentOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties voor het importeren van een ingebed document."
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Biedt opties voor het importeren van een ingebed document.

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

| Constructor | Beschrijving |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Initialiseert een nieuw exemplaar van de [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) klasse. |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Initialiseert een nieuw exemplaar van de [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getObjectData()](#getObjectData--) | De gegevens van het ingesloten object. |
| [getExtension()](#getExtension--) | De extensie van het ingesloten object. |
| [getPageNumber()](#getPageNumber--) | Het paginanummer voor het invoegen van het ingesloten object. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Haalt afbeeldingsgegevens op van het ingesloten object. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objectData | byte[] | De gegevens van het ingesloten object. |
| extensie | java.lang.String | De extensie van het ingesloten object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Initialiseert een nieuw exemplaar van de [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |
| pageNumber | int | Het paginanummer voor het toevoegen van een ingebed object. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


De gegevens van het ingesloten object.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


De extensie van het ingesloten object.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Het paginanummer voor het invoegen van het ingesloten object.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Haalt afbeeldingsgegevens op van het ingesloten object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |

**Returns:**
byte[]
