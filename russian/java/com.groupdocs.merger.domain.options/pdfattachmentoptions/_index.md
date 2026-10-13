---
title: "PdfAttachmentOptions"
second_title: "Справочник API GroupDocs.Merger для Java"
description: "Предоставляет параметры для вложения встроенного объекта в PDF."
type: docs
weight: 28
url: /ru/java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Предоставляет параметры для вложения встроенного объекта в PDF.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Инициализирует новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Инициализирует новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Инициализирует новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectData | byte[] | Данные встроенного объекта. |
| расширение | java.lang.String | Расширение встроенного объекта. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Инициализирует новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |

