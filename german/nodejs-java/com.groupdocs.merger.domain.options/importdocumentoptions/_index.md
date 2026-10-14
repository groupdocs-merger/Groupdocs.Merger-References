---
title: "ImportDocumentOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen für den Import eingebetteter Dokumente."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Bietet Optionen für den Import eingebetteter Dokumente.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Initialisiert eine neue Instanz der [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) Klasse. |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Initialisiert eine neue Instanz der [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getObjectData()](#getObjectData--) | Die Daten des eingebetteten Objekts. |
| [getExtension()](#getExtension--) | Die Erweiterung des eingebetteten Objekts. |
| [getPageNumber()](#getPageNumber--) | Die Seitenzahl für das Einfügen des eingebetteten Objekts. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Liest Bilddaten des eingebetteten Objekts. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Initialisiert eine neue Instanz der [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectData | byte[] | Die Daten des eingebetteten Objekts. |
| Erweiterung | java.lang.String | Die Erweiterung des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Initialisiert eine neue Instanz der [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |
| pageNumber | int | Die Seitennummer zum Hinzufügen des eingebetteten Objekts. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Die Daten des eingebetteten Objekts.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Die Erweiterung des eingebetteten Objekts.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Die Seitenzahl für das Einfügen des eingebetteten Objekts.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Liest Bilddaten des eingebetteten Objekts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |

**Returns:**
byte[]
