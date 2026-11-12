---
title: "PdfAttachmentOptions"
second_title: "GroupDocs.Merger Java용 API 레퍼런스"
description: "임베드된 객체를 PDF에 첨부하기 위한 옵션을 제공합니다."
type: docs
weight: 28
url: /ko/java/com.groupdocs.merger.domain.options/pdfattachmentoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPdfAttachmentOptions](../../com.groupdocs.merger.domain.options.interfaces/ipdfattachmentoptions)
```
public class PdfAttachmentOptions extends ImportDocumentOptions implements IPdfAttachmentOptions
```

임베드된 객체를 PDF에 첨부하기 위한 옵션을 제공합니다.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfAttachmentOptions(byte[] objectData, String extension)](#PdfAttachmentOptions-byte---java.lang.String-) | 새로운 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 클래스 인스턴스를 초기화합니다. |
| [PdfAttachmentOptions(String filePath)](#PdfAttachmentOptions-java.lang.String-) | 새로운 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 클래스 인스턴스를 초기화합니다. |
### PdfAttachmentOptions(byte[] objectData, String extension) {#PdfAttachmentOptions-byte---java.lang.String-}
```
public PdfAttachmentOptions(byte[] objectData, String extension)
```


새로운 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| objectData | byte[] | 삽입된 객체의 데이터입니다. |
| 확장자 | java.lang.String | 삽입된 객체의 확장자입니다. |

### PdfAttachmentOptions(String filePath) {#PdfAttachmentOptions-java.lang.String-}
```
public PdfAttachmentOptions(String filePath)
```


새로운 [PdfAttachmentOptions](../../com.groupdocs.merger.domain.options/pdfattachmentoptions) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 임베디드 객체의 파일 경로. |

