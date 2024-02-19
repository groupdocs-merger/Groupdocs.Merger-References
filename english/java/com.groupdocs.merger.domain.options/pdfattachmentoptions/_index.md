---
title: PdfAttachmentOptions
second_title: GroupDocs.Merger for Java API Reference
description: Provides options to attach the embedded object to Pdf.
type: docs
weight: 27
url: /java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Provides options to attach the embedded object to Pdf.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Initializes a new instance of the [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) class. |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Initializes a new instance of the [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) class. |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Initializes a new instance of the [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| objectData | byte[] | The data of the embedded object. |
| extension | java.lang.String | The extension of the embedded object. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Initializes a new instance of the [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path of the embedded object. |

