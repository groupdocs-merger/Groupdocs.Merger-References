---
title: FileType
second_title: .NET API 참조용 GroupDocs.Merger
description: 파일 형식을 나타냅니다. 에서 지원하는 모든 파일 형식 목록을 얻을 수 있는 방법을 제공합니다.GroupDocs.합병  확장자 등으로 파일 유형 감지
type: docs
weight: 100
url: /ko/net/groupdocs.merger.domain/filetype/
---
## FileType class

파일 형식을 나타냅니다. 에서 지원하는 모든 파일 형식 목록을 얻을 수 있는 방법을 제공합니다.**GroupDocs.합병** , 확장자 등으로 파일 유형 감지

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | 파일 이름 접미사(마침표 "." 포함) 예: ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | 파일 유형 이름 예: "Microsoft Word 문서". |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | 파일 확장자를 파일 유형에 매핑합니다. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 것과 동일합니다[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | 현재 여부를 결정합니다.[`FileType`](../filetype) 지정된 개체와 동일합니다. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | 현재 해시 코드를 반환합니다.[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | 현재 개체를 나타내는 문자열을 반환합니다. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | 지원되는 파일 유형 검색 |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | 입력 여부를 결정합니다.[`FileType`](../filetype) 아카이브 형식입니다. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | 입력 여부를 결정합니다.[`FileType`](../filetype) 이미지 형식입니다. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | 입력 여부를 결정합니다.[`FileType`](../filetype) 기본 텍스트 형식입니다. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | 여부를 결정합니다.[`FileType`](../filetype) 객체는 동일합니다. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | 여부를 결정합니다.[`FileType`](../filetype) 개체가 동일하지 않습니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | 비트맵 이미지 파일(.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용되는 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 압축 파일(.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | 쉼표로 구분된 값 파일(.csv)은 쉼표로 구분된 값이 있는 데이터 레코드가 포함된 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word 문서(.doc)는 Microsoft Word 또는 기타 워드 프로세싱 문서에서 생성된 이진 파일 형식의 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML 매크로 사용 문서(.docm) 파일은 매크로를 실행할 수 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML 문서(.docx)는 Microsoft Word 문서의 잘 알려진 형식입니다. 2007년부터 Microsoft Office 2007 출시와 함께 도입된 이 새로운 문서 형식의 구조는 일반 바이너리에서 XML과 바이너리 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word 문서 템플릿(.dot) 파일은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML 매크로 사용 문서 템플릿(.dotm)은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML 문서 템플릿(.dotx)은 Microsoft Word에서 추가 DOCX 파일 생성을 위한 미리 서식이 지정된 설정을 갖도록 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File(.epub)은 발행인과 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 현재 매우 일반적이어서 많은 e-reader 및 소프트웨어 응용 프로그램에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | 오류 로그 파일(.err)은 프로그램에서 생성된 오류 메시지를 포함하는 텍스트 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | 그래픽 교환 형식 파일(.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip 압축 파일(.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language 파일(.html)은 브라우저에 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG 이미지(.jpeg)는 손실 압축 방식을 사용하여 저장되는 일종의 이미지 형식입니다. 압축 결과 출력 이미지는 저장소 크기와 이미지 품질 간의 절충안입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG 이미지(.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML 웹 아카이브(.mht)는 다양한 응용 프로그램에서 만들 수 있는 웹 페이지 아카이브 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML 파일(.mhtml)은 다양한 응용 프로그램에서 만들 수 있는 웹 페이지 아카이브 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument 프레젠테이션(.odp)은 OASISOpen 표준에서 OpenOffice.org에서 사용하는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument 스프레드시트(.ods) 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument 텍스트 문서(.odt) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 응용 프로그램으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote 문서(.one) 파일은 Microsoft OneNote 응용 프로그램에서 생성됩니다. OneNote를 사용하면 메모를 작성하기 위해 드래프트 패드를 사용하는 것처럼 응용 프로그램을 사용하여 정보를 수집할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument 프레젠테이션 템플릿(.otp)은 OASIS OpenDocument 표준 형식의 응용 프로그램에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument 문서 템플릿(.ott)은 OASIS의 OpenDocument 표준 형식을 준수하는 응용 프로그램에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | PDF(Portable Document Format File)는 응용 프로그램 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 문서 및 기타 참조 자료를 표현하기 위한 표준으로 도입된 파일 형식입니다. 이 파일에 대해 자세히 알아보기 체재[여기](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | 휴대용 네트워크 그래픽(.png)은 무손실 압축을 사용하는 일종의 래스터 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint 슬라이드 쇼(.pps)는 슬라이드 쇼 목적으로 Microsoft PowerPoint를 사용하여 만든 파일입니다. PPS 파일 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML 슬라이드 쇼(.ppsx)는 슬라이드 쇼 목적으로 Microsoft PowerPoint 2007 이상을 사용하여 만든 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint 프레젠테이션(.ppt)은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. Microsoft PowerPoint 97-2003에서 사용하는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML 프레젠테이션(.pptx)은 널리 사용되는 Microsoft PowerPoint 응용 프로그램으로 만든 프레젠테이션 파일입니다. 프레젠테이션 파일 형식 PPT의 이전 버전인 바이너리와 달리 PPTX 형식은 Microsoft PowerPoint 개방형 XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | 포스트스크립트 파일(.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive 압축 파일(.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | 서식 있는 텍스트 형식 파일(.rtf) Microsoft에서 도입하고 문서화한 RTF(서식 있는 텍스트 형식)는 응용 프로그램 내에서 사용하기 위해 형식이 지정된 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip 압축 파일(.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | 통합 Unix 파일 아카이브(.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX 소스 문서(.tex)는 문서 조판에 사용되는 프로그래밍 및 마크업 기능으로 구성된 언어입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | 태그가 지정된 이미지 파일(.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | 태그가 지정된 이미지 파일 형식(.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | 탭으로 구분된 값 파일(.tsv)은 일반 텍스트 형식의 탭으로 구분된 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | 일반 텍스트 파일(.txt)은 일반 텍스트를 줄 형태로 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio 드로잉 XML 파일(.vdx)은 Microsoft Visio에서 생성된 드로잉 또는 차트이지만 XML 형식으로 저장되며 확장자는 .VDX입니다. Visio 드로잉 XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing(.vsdm)은 매크로를 지원하는 Microsoft Visio 응용 프로그램으로 만든 드로잉 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 도면이지만 파일을 열 때 매크로를 실행할 수 있는 기능도 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing(.vsdx)은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이전 버전의 Microsoft Visio에서 지원하는 이진 파일 형식인 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio 매크로 사용 스텐실 파일(.vssm)은 매크로 지원을 제공하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 모양의 원하는 서식 및 배치를 얻을 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio 스텐실 파일(.vssx)은 Microsoft Visio 2013 이상에서 만든 드로잉 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 셰이프 컬렉션, 커넥터, 순서도, 네트워크 레이아웃, UML 다이어그램, 와 같은 다양한 드로잉 요소를 표현하는 것으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio 매크로 사용 드로잉 템플릿(.vstm)은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 VBA(Visual Basic for Applications) 코드로 개발된 매크로를 실행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio 드로잉 템플릿(.vstx)은 Microsoft Visio 2013 이상에서 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃 및 설정과 함께 .VSDX 파일로 저장된 Visio 드로잉을 만들기 위한 시작점을 제공합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio 스텐실 XML 파일(.vsx)은 Microsoft Visio에서 다이어그램을 만드는 데 사용되는 드로잉 및 도형으로 구성된 스텐실을 나타냅니다. VSX 파일은 XML 파일 형식으로 저장되며 Visio 2013까지 지원되었습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio 템플릿 XML 파일(.vtx)은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 템플릿은 동일한 설정의 여러 Visio 파일을 만드는 데 사용할 수 있는 기본 설정이 포함된 파일을 제공하는 것을 목표로 합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel 매크로 사용 추가 기능(.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel 스프레드시트(.xls)는 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 기타 유사한 스프레드시트 프로그램에서 생성할 수 있는 파일입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel 이진 스프레드시트(.xlsb) 파일 형식은 Excel 통합 문서 콘텐츠를 지정하는 레코드 및 구조의 모음인 Excel 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML 매크로 사용 스프레드시트(.xlsm)는 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML 스프레드시트(.xlsx)는 Microsoft Office 2007 릴리스와 함께 Microsoft에서 도입한 잘 알려진 Microsoft Excel 문서 형식입니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel 템플릿 파일(.xlt)은 Microsoft Office 제품군의 일부로 제공되는 스프레드시트 응용 프로그램인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새 XLT 파일 생성 및 열기를 지원했습니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML 매크로 사용 스프레드시트 템플릿(.xltm)은 Microsoft Excel에서 매크로 사용 템플릿 파일로 생성된 파일을 나타냅니다. XLTM 파일은 XLTX가 매크로로 템플릿 파일 생성을 지원하지 않는다는 점을 제외하면 구조상 XLTX와 유사합니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML 스프레드시트 템플릿(.xltx) 파일은 Office OpenXML 파일 형식 사양을 기반으로 합니다. XLTX 파일에 지정된 것과 동일한 설정을 나타내는 XLSX 파일을 생성하는 데 활용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper 사양 파일(.xps)은 Microsoft에서 만든 XML Paper 사양을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보기[여기](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | 압축 파일(.zip) |

### 비고

**더 알아보기**

* GroupDocs.Merger: 에서 지원하는 파일 형식에 대해 자세히 알아보십시오.[지원되는 문서 형식의 전체 목록](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* 코드에서 지원되는 파일 형식 가져오기에 대해 자세히 알아보기: [코드에서 지원되는 파일 형식을 얻는 방법](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### 또한보십시오

* 네임스페이스 [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* 집회 [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
