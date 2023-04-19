---
title: OleDiagramOptions
second_title: .NET API 참조용 GroupDocs.Merger
description: OLE를 통해 포함된 문서를 다이어그램으로 가져오기 위한 옵션을 제공합니다.
type: docs
weight: 440
url: /ko/net/groupdocs.merger.domain.options/olediagramoptions/
---
## OleDiagramOptions class

OLE를 통해 포함된 문서를 다이어그램으로 가져오기 위한 옵션을 제공합니다.

```csharp
public class OleDiagramOptions : ImportDocumentOptions, IOleDiagramOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OleDiagramOptions](olediagramoptions#constructor_2)(string, int) | 의 새 인스턴스를 초기화합니다.[`OleDiagramOptions`](../olediagramoptions) 클래스. |
| [OleDiagramOptions](olediagramoptions#constructor_1)(string, byte[], int) | 의 새 인스턴스를 초기화합니다.[`OleDiagramOptions`](../olediagramoptions) 클래스. |
| [OleDiagramOptions](olediagramoptions#constructor)(byte[], byte[], string, int) | 의 새 인스턴스를 초기화합니다.[`OleDiagramOptions`](../olediagramoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.merger.domain.options/importdocumentoptions/extension) { get; } | 포함 개체의 확장자입니다. |
| [Height](../../groupdocs.merger.domain.options/olediagramoptions/height) { get; set; } | 포함된 개체 모양의 높이(인치)입니다. |
| [ImageData](../../groupdocs.merger.domain.options/olediagramoptions/imagedata) { get; } | 임베디드 개체의 이미지 데이터입니다. |
| [ObjectData](../../groupdocs.merger.domain.options/importdocumentoptions/objectdata) { get; } | 임베디드 개체의 데이터입니다. |
| [PageNumber](../../groupdocs.merger.domain.options/importdocumentoptions/pagenumber) { get; } | 포함 개체 삽입을 위한 페이지 번호입니다. |
| [Width](../../groupdocs.merger.domain.options/olediagramoptions/width) { get; set; } | 포함된 개체 모양의 너비(인치)입니다. |
| [X](../../groupdocs.merger.domain.options/olediagramoptions/x) { get; set; } | 페이지를 기준으로 포함된 개체 모양 핀(회전 중심)의 X 좌표입니다. |
| [Y](../../groupdocs.merger.domain.options/olediagramoptions/y) { get; set; } | 페이지를 기준으로 포함된 개체 모양 핀(회전 중심)의 Y 좌표입니다. |

### 비고

**더 알아보기**

* OLE: 를 통해 다이어그램에 문서 추가에 대한 추가 정보[OLE를 통해 Diagram에 문서를 추가합니다.](https://docs.groupdocs.com/merger/net/add-document-to-diagram-via-ole/)

### 또한보십시오

* class [ImportDocumentOptions](../importdocumentoptions)
* interface [IOleDiagramOptions](../iolediagramoptions)
* 네임스페이스 [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* 집회 [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->