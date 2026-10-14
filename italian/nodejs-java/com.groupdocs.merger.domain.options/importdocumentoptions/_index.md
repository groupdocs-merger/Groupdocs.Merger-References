---
title: "ImportDocumentOptions"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Fornisce opzioni per l'importazione del documento incorporato."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Fornisce opzioni per l'importazione del documento incorporato.

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Inizializza una nuova istanza della classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Inizializza una nuova istanza della classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getObjectData()](#getObjectData--) | I dati dell'oggetto incorporato. |
| [getExtension()](#getExtension--) | L'estensione dell'oggetto incorporato. |
| [getPageNumber()](#getPageNumber--) | Il numero di pagina per l'inserimento dell'oggetto incorporato. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Ottiene i dati dell'immagine dell'oggetto incorporato. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Inizializza una nuova istanza della classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| objectData | byte[] | I dati dell'oggetto incorporato. |
| estensione | java.lang.String | L'estensione dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Inizializza una nuova istanza della classe [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |
| pageNumber | int | Il numero di pagina per aggiungere l'oggetto incorporato. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


I dati dell'oggetto incorporato.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


L'estensione dell'oggetto incorporato.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Il numero di pagina per l'inserimento dell'oggetto incorporato.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Ottiene i dati dell'immagine dell'oggetto incorporato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso file dell'oggetto incorporato. |

**Returns:**
byte[]
