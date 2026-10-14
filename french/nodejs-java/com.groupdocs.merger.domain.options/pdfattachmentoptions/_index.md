---
title: "PdfAttachmentOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Fournit des options pour attacher l'objet intégré au PDF."
type: docs
weight: 27
url: /fr/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Fournit des options pour attacher l'objet intégré au PDF.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Initialise une nouvelle instance de la classe [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Initialise une nouvelle instance de la classe [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Initialise une nouvelle instance de la classe [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| objectData | byte[] | Les données de l'objet intégré. |
| extension | java.lang.String | L'extension de l'objet intégré. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Initialise une nouvelle instance de la classe [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin d'accès du fichier de l'objet incorporé. |

