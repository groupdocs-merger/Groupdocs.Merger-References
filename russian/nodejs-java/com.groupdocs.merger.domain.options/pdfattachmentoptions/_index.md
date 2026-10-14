---
title: "PdfAttachmentOptions"
second_title: "Пространство имён com.groupdocs.merger.domain.builders предоставляет построители."
description: "Предоставляет параметры для присоединения встроенного объекта к PDF."
type: docs
weight: 27
url: /ru/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

Предоставляет параметры для присоединения встроенного объекта к PDF.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | Создаёт новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | Создаёт новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions). |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


Создаёт новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| objectData | byte[] | Данные встроенного объекта. |
| расширение | java.lang.String | Расширение встроенного объекта. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


Создаёт новый экземпляр класса [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | java.lang.String | Путь к файлу встроенного объекта. |

