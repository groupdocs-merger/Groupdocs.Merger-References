---
title: "PdfAttachmentOptions"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Bietet Optionen zum Anhängen des eingebetteten Objekts an PDF."
type: docs
weight: 27
url: /de/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Bietet Optionen zum Anhängen des eingebetteten Objekts an PDF.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Initialisiert eine neue Instanz der [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) Klasse. |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Initialisiert eine neue Instanz der [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) Klasse. |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Initialisiert eine neue Instanz der [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objectData | byte[] | Die Daten des eingebetteten Objekts. |
| Erweiterung | java.lang.String | Die Erweiterung des eingebetteten Objekts. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Initialisiert eine neue Instanz der [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad des eingebetteten Objekts. |

