---
title: "PdfAttachmentOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供将嵌入对象附加到 PDF 的选项。"
type: docs
weight: 27
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

提供将嵌入对象附加到 PDF 的选项。

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | 初始化 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 类的新实例。 |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | 初始化 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 类的新实例。 |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


初始化 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectData | byte[] | 嵌入对象的数据。 |
| 扩展名 | java.lang.String | 嵌入对象的扩展名。 |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


初始化 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |

