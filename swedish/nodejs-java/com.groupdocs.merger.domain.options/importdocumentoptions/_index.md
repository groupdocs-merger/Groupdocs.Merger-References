---
title: "ImportDocumentOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för import av inbäddat dokument."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Tillhandahåller alternativ för import av inbäddat dokument.

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Initierar en ny instans av klassen [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Initierar en ny instans av klassen [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getObjectData()](#getObjectData--) | Data för det inbäddade objektet. |
| [getExtension()](#getExtension--) | Filändelse för det inbäddade objektet. |
| [getPageNumber()](#getPageNumber--) | Sidnummer för infogning av det inbäddade objektet. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Hämtar bilddata för det inbäddade objektet. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Initierar en ny instans av klassen [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectData | byte[] | Data för det inbäddade objektet. |
| filändelse | java.lang.String | Filändelse för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Initierar en ny instans av klassen [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |
| pageNumber | int | Sidnumret för att lägga till ett inbäddat objekt. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Data för det inbäddade objektet.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Filändelse för det inbäddade objektet.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Sidnummer för infogning av det inbäddade objektet.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Hämtar bilddata för det inbäddade objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |

**Returns:**
byte[]
