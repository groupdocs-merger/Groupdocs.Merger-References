---
title: "PdfAttachmentOptions"
second_title: "GroupDocs.Merger för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för att bifoga det inbäddade objektet till PDF."
type: docs
weight: 27
url: /sv/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Tillhandahåller alternativ för att bifoga det inbäddade objektet till PDF.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Initierar en ny instans av klassen [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Initierar en ny instans av klassen [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Initierar en ny instans av klassen [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objectData | byte[] | Data för det inbäddade objektet. |
| filändelse | java.lang.String | Filändelse för det inbäddade objektet. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Initierar en ny instans av klassen [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen för det inbäddade objektet. |

