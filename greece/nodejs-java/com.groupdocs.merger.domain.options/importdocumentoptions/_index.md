---
title: "ImportDocumentOptions"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Παρέχει επιλογές για την εισαγωγή ενσωματωμένου εγγράφου."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Παρέχει επιλογές για την εισαγωγή ενσωματωμένου εγγράφου.

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

| Constructor | Περιγραφή |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getObjectData()](#getObjectData--) | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| [getExtension()](#getExtension--) | Η επέκταση του ενσωματωμένου αντικειμένου. |
| [getPageNumber()](#getPageNumber--) | Ο αριθμός σελίδας για την εισαγωγή του ενσωματωμένου αντικειμένου. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Λαμβάνει τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| objectData | byte[] | Τα δεδομένα του ενσωματωμένου αντικειμένου. |
| επέκταση | java.lang.String | Η επέκταση του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |
| pageNumber | int | Ο αριθμός σελίδας για την προσθήκη ενσωματωμένου αντικειμένου. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Τα δεδομένα του ενσωματωμένου αντικειμένου.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Η επέκταση του ενσωματωμένου αντικειμένου.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Ο αριθμός σελίδας για την εισαγωγή του ενσωματωμένου αντικειμένου.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Λαμβάνει τα δεδομένα εικόνας του ενσωματωμένου αντικειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η διαδρομή αρχείου του ενσωματωμένου αντικειμένου. |

**Returns:**
byte[]
