---
title: "PdfAttachmentOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "埋め込みオブジェクトをPdfに添付するためのオプションを提供します。"
type: docs
weight: 28
url: /ja/java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

埋め込みオブジェクトをPdfに添付するためのオプションを提供します。

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | 新しい [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) クラスのインスタンスを初期化します。 |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | 新しい [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) クラスのインスタンスを初期化します。 |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


新しい [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータです。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子です。 |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


新しい [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |

