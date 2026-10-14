---
title: "PdfAttachmentOptions"
second_title: "De com.groupdocs.merger.domain.builders namespace biedt builders."
description: "Biedt opties om het ingebedde object aan Pdf te koppelen."
type: docs
weight: 27
url: /nl/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Biedt opties om het ingebedde object aan Pdf te koppelen.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Initialiseert een nieuw exemplaar van de [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) klasse. |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Initialiseert een nieuw exemplaar van de [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) klasse. |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Initialiseert een nieuw exemplaar van de [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| objectData | byte[] | De gegevens van het ingesloten object. |
| extensie | java.lang.String | De extensie van het ingesloten object. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Initialiseert een nieuw exemplaar van de [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad van het ingebedde object. |

