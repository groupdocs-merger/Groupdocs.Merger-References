---
title: "PdfAttachmentOptions"
second_title: "Referencia de API de GroupDocs.Merger para Node.js vía Java"
description: "Proporciona opciones para adjuntar el objeto incrustado al PDF."
type: docs
weight: 27
url: /es/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Proporciona opciones para adjuntar el objeto incrustado al PDF.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Inicializa una nueva instancia de la clase [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Inicializa una nueva instancia de la clase [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Inicializa una nueva instancia de la clase [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| objectData | byte[] | Los datos del objeto incrustado. |
| extensión | java.lang.String | La extensión del objeto incrustado. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Inicializa una nueva instancia de la clase [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | java.lang.String | La ruta del archivo del objeto incrustado. |

