---
title: "FileType"
second_title: "com.groupdocs.merger.domain.builders 네임스페이스는 빌더를 제공합니다."
description: "파일 형식을 나타냅니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

파일 형식을 나타냅니다. **GroupDocs.Merger**에서 지원하는 모든 파일 형식 목록을 가져오고, 확장자를 통해 파일 형식을 감지하는 등의 메서드를 제공합니다.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Fields

| Field | 설명 |
| --- | --- |
| [Unknown](#Unknown) | 알 수 없는 파일 형식을 나타냅니다. |
| [ZIP](#ZIP) | 압축 파일 (.zip) |
| [SevenZ](#SevenZ) | 7-Zip 압축 파일 (.7z) |
| [TAR](#TAR) | 통합 유닉스 파일 아카이브 (.tar) |
| [RAR](#RAR) | Roshal ARchive 압축 파일 (.rar) |
| [VSSX](#VSSX) | Visio 스텐실 파일 (.vssx)은 Microsoft Visio 2013 이상에서 만든 드로잉 스텐실입니다. |
| [VSDX](#VSDX) | Visio 드로잉 (.vsdx)은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. |
| [VSDM](#VSDM) | Visio 매크로 지원 드로잉 (.vsdm)은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 드로잉 파일입니다. |
| [VSTX](#VSTX) | Visio 드로잉 템플릿 (.vstx)은 Microsoft Visio 2013 이상에서 만든 드로잉 템플릿 파일입니다. |
| [VSTM](#VSTM) | Visio 매크로 지원 드로잉 템플릿 (.vstm)은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. |
| [VSSM](#VSSM) | Visio 매크로 지원 스텐실 파일 (.vssm)은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. |
| [VSX](#VSX) | Visio 스텐실 XML 파일 (.vsx)은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 드로잉 및 도형으로 구성된 스텐실을 의미합니다. |
| [VTX](#VTX) | Visio 템플릿 XML 파일 (.vtx)은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. |
| [VDX](#VDX) | Visio 드로잉 XML 파일 (.vdx)은 Microsoft Visio에서 만든 드로잉 또는 차트이지만 XML 형식으로 저장되어 .VDX 확장자를 가집니다. |
| [EPUB](#EPUB) | Open eBook 파일 (.epub)은 출판사와 소비자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. |
| [BMP](#BMP) | Bitmap 이미지 파일 (.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용되는 파일을 나타냅니다. |
| [JPG](#JPG) | JPEG 이미지 (.jpg) |
| [JPEG](#JPEG) | JPEG 이미지 (.jpeg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. |
| [PNG](#PNG) | Portable Network Graphic (.png)은 무손실 압축을 사용하는 래스터 이미지 파일 형식입니다. |
| [PS](#PS) | PostScript 파일 (.ps) |
| [TIF](#TIF) | Tagged Image 파일 (.tif) |
| [TIFF](#TIFF) | Tagged Image 파일 형식 (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format 파일 (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics 파일 (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics 압축 파일 (.svgz) |
| [EMF](#EMF) | Windows 향상 메타파일 (.emf) |
| [EMZ](#EMZ) | Windows 압축 향상 메타파일 (.emz) |
| [HTML](#HTML) | Hypertext Markup Language 파일 (.html)은 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. |
| [MHT](#MHT) | MHTML 웹 아카이브 (.mht)는 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식입니다. |
| [MHTML](#MHTML) | MIME HTML 파일 (.mhtml)은 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식입니다. |
| [ONE](#ONE) | OneNote 문서 (.one) 파일은 Microsoft OneNote 애플리케이션으로 생성됩니다. |
| [PDF](#PDF) | Portable Document Format 파일 (.pdf)은 문서 및 기타 참고 자료를 애플리케이션 소프트웨어, 하드웨어 및 운영 체제와 독립적인 형식으로 표현하기 위한 표준으로 도입된 파일 형식입니다. |
| [XPS](#XPS) | XML Paper Specification 파일 (.xps)은 Microsoft가 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. |
| [TEX](#TEX) | LaTeX 소스 문서 (.tex)는 프로그래밍과 마크업 기능을 모두 포함하는 언어로, 문서 조판에 사용됩니다. |
| [PPT](#PPT) | PowerPoint 프레젠테이션 (.ppt)은 슬라이드 쇼로 표시하기 위한 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. |
| [PPTX](#PPTX) | PowerPoint Open XML 프레젠테이션 (.pptx)은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. |
| [PPS](#PPS) | PowerPoint 슬라이드 쇼 (.pps)는 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용해 만든 파일입니다. |
| [PPSX](#PPSX) | PowerPoint Open XML 슬라이드 쇼 (.ppsx)는 Microsoft PowerPoint 2007 이상을 사용해 슬라이드 쇼 용도로 만든 파일입니다. |
| [ODP](#ODP) | OpenDocument 프레젠테이션 (.odp)은 OASIS Open 표준에서 OpenOffice.org가 사용하는 프레젠테이션 파일 형식을 나타냅니다. |
| [OTP](#OTP) | OpenDocument 프레젠테이션 템플릿 (.otp)은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 만든 프레젠테이션 템플릿 파일을 나타냅니다. |
| [XLS](#XLS) | Excel 스프레드시트 (.xls)는 Microsoft Excel뿐만 아니라 OpenOffice Calc나 Apple Numbers와 같은 유사한 스프레드시트 프로그램으로도 만들 수 있는 파일입니다. |
| [XLSX](#XLSX) | Microsoft Excel Open XML 스프레드시트 (.xlsx)는 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서의 잘 알려진 형식입니다. |
| [XLSM](#XLSM) | Excel Open XML 매크로 사용 스프레드시트 (.xlsm)는 매크로를 지원하는 스프레드시트 파일 유형입니다. |
| [XLSB](#XLSB) | Excel 바이너리 스프레드시트 (.xlsb) 파일 형식은 Excel 워크북 내용을 정의하는 레코드와 구조의 집합인 Excel 바이너리 파일 형식을 지정합니다. |
| [CSV](#CSV) | 쉼표로 구분된 값 파일 (.csv)은 쉼표로 구분된 데이터 레코드를 포함하는 일반 텍스트 파일을 나타냅니다. |
| [TSV](#TSV) | 탭으로 구분된 값 파일 (.tsv)은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. |
| [ODS](#ODS) | OpenDocument 스프레드시트 (.ods). |
| [XLTM](#XLTM) | Excel Open XML 매크로 사용 스프레드시트 템플릿 (.xltm)은 Microsoft Excel이 매크로 사용 템플릿 파일로 생성하는 파일을 나타냅니다. |
| [XLTX](#XLTX) | Excel Open XML 스프레드시트 템플릿 (.xltx) 파일은 Office OpenXML 파일 형식 사양을 기반으로 합니다. |
| [XLT](#XLT) | Excel 템플릿 파일 (.xlt)은 Microsoft Office 제품군에 포함된 스프레드시트 애플리케이션인 Microsoft Excel로 만든 템플릿 파일입니다. |
| [XLAM](#XLAM) | Excel 매크로 사용 가능 추가 기능 (.xlam). |
| [DOC](#DOC) | Microsoft Word 문서 (.doc)는 Microsoft Word 또는 기타 워드 프로세서에서 생성된 문서를 이진 파일 형식으로 나타냅니다. |
| [DOCX](#DOCX) | Microsoft Word Open XML 문서 (.docx)는 Microsoft Word 문서에 널리 알려진 형식입니다. |
| [DOCM](#DOCM) | Word Open XML 매크로 사용 가능 문서 (.docm) 파일은 매크로 실행 기능이 있는 Microsoft Word 2007 이상에서 생성된 문서입니다. |
| [DOT](#DOT) | Word 문서 템플릿 (.dot) 파일은 추가 DOC 또는 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 가진 Microsoft Word에서 만든 템플릿 파일입니다. |
| [DOTX](#DOTX) | Word Open XML 문서 템플릿 (.dotx)은 추가 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 가진 Microsoft Word에서 만든 템플릿 파일입니다. |
| [DOTM](#DOTM) | Word Open XML 매크로 사용 가능 문서 템플릿 (.dotm)은 Microsoft Word 2007 이상으로 만든 템플릿 파일을 나타냅니다. |
| [RTF](#RTF) | Rich Text Format 파일 (.rtf)은 Microsoft에서 도입하고 문서화했으며, Rich Text Format(RTF)은 애플리케이션 내에서 사용되는 서식 있는 텍스트와 그래픽을 인코딩하는 방법을 나타냅니다. |
| [TXT](#TXT) | Plain Text 파일 (.txt)은 줄 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. |
| [ERR](#ERR) | Error Log 파일 (.err)은 프로그램에서 생성된 오류 메시지를 포함하는 텍스트 파일입니다. |
| [ODT](#ODT) | OpenDocument 텍스트 문서 (.odt) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세서 애플리케이션으로 만든 문서 유형입니다. |
| [OTT](#OTT) | OpenDocument 문서 템플릿 (.ott)은 OASIS의 OpenDocument 표준 형식에 부합하도록 애플리케이션에서 생성한 템플릿 문서를 나타냅니다. |
| [WAV](#WAV) | WAV는 WAVE(웨이브폼 오디오 파일 포맷)로 알려져 있으며, 디지털 오디오 파일을 저장하기 위한 Microsoft의 리소스 교환 파일 포맷(RIFF) 사양의 하위 집합입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 파일 유형 이름 예시. |
| [getExtension()](#getExtension--) | 파일명 접미사(점 "." 포함) 예시. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | 파일 확장자를 파일 유형에 매핑합니다. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | 지원되는 파일 유형을 검색합니다. |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | 현재 [FileType](../../com.groupdocs.merger.domain/filetype)가 지정된 [FileType](../../com.groupdocs.merger.domain/filetype) 객체와 동일한지 확인합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 현재 [FileType](../../com.groupdocs.merger.domain/filetype)가 지정된 객체와 동일한지 확인합니다. |
| [hashCode()](#hashCode--) | 현재 [FileType](../../com.groupdocs.merger.domain/filetype) 객체의 해시 코드를 반환합니다. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 두 [FileType](../../com.groupdocs.merger.domain/filetype) 객체가 동일한지 확인합니다. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 두 [FileType](../../com.groupdocs.merger.domain/filetype) 객체가 동일하지 않은지 확인합니다. |
| [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | 입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 기본 텍스트 형식인지 확인합니다. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | 입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 아카이브 형식인지 확인합니다. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | 입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 기본 텍스트 형식인지 확인합니다. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | 입력된 [FileType](../../com.groupdocs.merger.domain/filetype)이 오디오 형식인지 여부를 결정합니다. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


알 수 없는 파일 형식을 나타냅니다.

### ZIP {#ZIP}
```
public static FileType ZIP
```


압축 파일 (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


7-Zip 압축 파일 (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


통합 유닉스 파일 아카이브 (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal ARchive 압축 파일 (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio 스텐실 파일(.vssx)은 Microsoft Visio 2013 이상으로 만든 드로잉 스텐실입니다. VSSX 파일 형식은 Visio 2013 이상에서 열 수 있습니다. Visio 파일은 도형, 커넥터, 플로우차트, 네트워크 레이아웃, UML 다이어그램 등 다양한 드로잉 요소를 표현하는 것으로 알려져 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing(.vsdx)은 Microsoft Office 2013부터 도입된 Microsoft Visio 파일 형식을 나타냅니다. 이는 이전 버전 Microsoft Visio에서 지원하던 이진 파일 형식 .VSD를 대체하기 위해 개발되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio 매크로 사용 가능 드로잉(.vsdm)은 매크로를 지원하는 Microsoft Visio 애플리케이션으로 만든 드로잉 파일입니다. VSDM 파일은 VSDX와 유사한 OPC/XML 드로잉이지만 파일이 열릴 때 매크로를 실행할 수 있는 기능도 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing 템플릿(.vstx)은 Microsoft Visio 2013 이상으로 만든 드로잉 템플릿 파일입니다. 이러한 VSTX 파일은 기본 레이아웃 및 설정이 적용된 .VSDX 파일 형태의 Visio 드로잉을 만들기 위한 시작점을 제공합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio 매크로 사용 가능 드로잉 템플릿(.vstm)은 매크로를 지원하는 Microsoft Visio로 만든 템플릿 파일입니다. VSDX 파일과 달리 VSTM 템플릿에서 만든 파일은 Visual Basic for Applications(VBA) 코드로 개발된 매크로를 실행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio 매크로 사용 가능 스텐실 파일(.vssm)은 매크로를 지원하는 Microsoft Visio 스텐실 파일입니다. VSSM 파일을 열면 매크로를 실행하여 다이어그램에서 도형의 원하는 형식 지정 및 배치를 수행할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio 스텐실 XML 파일(.vsx)은 Microsoft Visio에서 다이어그램을 만들 때 사용되는 드로잉 및 도형으로 구성된 스텐실을 의미합니다. VSX 파일은 XML 형식으로 저장되며 Visio 2013까지 지원되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio 템플릿 XML 파일(.vtx)은 XML 파일 형식으로 디스크에 저장되는 Microsoft Visio 드로잉 템플릿입니다. 이 템플릿은 동일한 설정을 가진 여러 Visio 파일을 만들 때 사용할 수 있는 기본 설정을 제공하도록 설계되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML 파일(.vdx)은 Microsoft Visio에서 만든 드로잉 또는 차트이지만 .VDX 확장자를 가진 XML 형식으로 저장됩니다. Visio 드로잉 XML 파일은 Microsoft에서 개발한 Visio 소프트웨어에서 생성됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook 파일(.epub)은 출판사와 독자를 위한 표준 디지털 출판 형식을 제공하는 전자책 파일 형식입니다. 이 형식은 현재 매우 일반화되어 많은 전자책 리더와 소프트웨어 애플리케이션에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap 이미지 파일(.bmp)은 비트맵 디지털 이미지를 저장하는 데 사용되는 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG 이미지 (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG 이미지(.jpeg)는 손실 압축 방식을 사용하여 저장되는 이미지 형식입니다. 압축 결과로 생성된 출력 이미지는 저장 용량과 이미지 품질 사이의 균형을 이룹니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic(.png)은 무손실 압축을 사용하는 래스터 이미지 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript 파일 (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Tagged Image 파일 (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Tagged Image 파일 형식 (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Graphical Interchange Format 파일 (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Scalable Vector Graphics 파일 (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Scalable Vector Graphics 압축 파일 (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Windows 향상 메타파일 (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows 압축 향상 메타파일 (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language 파일(.html)은 브라우저에서 표시하기 위해 만든 웹 페이지의 확장자입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML 웹 아카이브(.mht)는 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML 파일(.mhtml)은 다양한 애플리케이션에서 생성할 수 있는 웹 페이지 아카이브 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote 문서(.one) 파일은 Microsoft OneNote 애플리케이션으로 생성됩니다. OneNote를 사용하면 마치 초안 패드처럼 정보를 수집할 수 있습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format 파일(.pdf)은 문서 및 기타 참고 자료를 애플리케이션, 하드웨어, 운영 체제와 무관하게 표준화된 형식으로 표현하기 위해 도입된 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification 파일(.xps)은 Microsoft에서 만든 XML Paper Specification을 기반으로 하는 페이지 레이아웃 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX 소스 문서(.tex)는 프로그래밍 및 마크업 기능을 포함하는 언어로, 문서 조판에 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint 프레젠테이션(.ppt)은 슬라이드 쇼로 표시되는 슬라이드 모음으로 구성된 PowerPoint 파일을 나타냅니다. 이는 Microsoft PowerPoint 97-2003에서 사용되는 이진 파일 형식을 지정합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML 프레젠테이션(.pptx)은 널리 사용되는 Microsoft PowerPoint 애플리케이션으로 만든 프레젠테이션 파일입니다. 이전 버전인 이진 PPT와 달리 PPTX 형식은 Microsoft PowerPoint Open XML 프레젠테이션 파일 형식을 기반으로 합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint 슬라이드 쇼(.pps)는 슬라이드 쇼 용도로 Microsoft PowerPoint를 사용해 만든 파일입니다. PPS 파일의 읽기 및 생성은 Microsoft PowerPoint 97-2003에서 지원됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML 슬라이드 쇼(.ppsx)는 Microsoft PowerPoint 2007 이상을 사용해 슬라이드 쇼 용도로 만든 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp)은 OpenOffice.org에서 OASISOpen 표준으로 사용되는 프레젠테이션 파일 형식을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp)은 OASIS OpenDocument 표준 형식으로 애플리케이션에서 생성된 프레젠테이션 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls)은 Microsoft Excel뿐만 아니라 OpenOffice Calc 또는 Apple Numbers와 같은 유사한 스프레드시트 프로그램에서도 생성할 수 있는 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx)은 Microsoft Office 2007 출시와 함께 Microsoft가 도입한 Microsoft Excel 문서용 잘 알려진 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm)은 매크로를 지원하는 스프레드시트 파일 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) 파일 형식은 Excel 바이너리 파일 형식을 지정하며, 이는 Excel 워크북 내용을 정의하는 레코드와 구조의 모음입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv)은 쉼표로 구분된 값으로 데이터 레코드를 포함하는 일반 텍스트 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv)은 탭으로 구분된 데이터를 일반 텍스트 형식으로 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument 스프레드시트 (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Excel Open XML Macro-Enabled Spreadsheet Template (.xltm)은 Microsoft Excel에서 매크로 사용이 가능한 템플릿 파일로 생성되는 파일을 나타냅니다. XLTM 파일은 구조가 XLTX와 유사하지만, 후자는 매크로가 포함된 템플릿 파일 생성을 지원하지 않습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) 파일은 Office OpenXML 파일 형식 사양을 기반으로 합니다. 이는 XLTX 파일에 지정된 동일한 설정을 가진 XLSX 파일을 생성하는 데 사용할 수 있는 표준 템플릿 파일을 만드는 데 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt)은 Microsoft Office 제품군에 포함된 스프레드시트 애플리케이션인 Microsoft Excel로 만든 템플릿 파일입니다. Microsoft Office 97-2003은 새로운 XLT 파일을 만들고 열 수 있었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel 매크로 사용 가능 추가 기능 (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc)은 Microsoft Word 또는 기타 워드 프로세서에서 이진 파일 형식으로 생성된 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx)은 Microsoft Word 문서용으로 널리 알려진 형식입니다. 2007년 Microsoft Office 2007 출시와 함께 도입되었으며, 이 새로운 문서 형식의 구조는 기존의 순수 이진 형식에서 XML과 이진 파일의 조합으로 변경되었습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) 파일은 매크로 실행 기능이 포함된 Microsoft Word 2007 이상에서 생성된 문서입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) 파일은 추가적인 DOC 또는 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) 파일은 추가적인 DOCX 파일 생성을 위해 미리 서식이 지정된 설정을 갖도록 Microsoft Word에서 만든 템플릿 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) 파일은 Microsoft Word 2007 이상에서 만든 템플릿 파일을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf)은 Microsoft가 도입하고 문서화한 형식으로, 서식이 적용된 텍스트와 그래픽을 애플리케이션 내에서 사용할 수 있도록 인코딩하는 방법을 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt)은 줄 형태의 일반 텍스트를 포함하는 텍스트 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Error Log File (.err)은 프로그램에서 생성된 오류 메시지를 포함하는 텍스트 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) 파일은 OpenDocument 텍스트 파일 형식을 기반으로 하는 워드 프로세싱 애플리케이션으로 만든 문서 유형입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) 파일은 OASIS의 OpenDocument 표준 형식에 부합하도록 애플리케이션에서 생성된 템플릿 문서를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV는 WAVE(웨이브폼 오디오 파일 포맷)로 알려져 있으며, 디지털 오디오 파일을 저장하기 위한 Microsoft의 리소스 인터체인지 파일 포맷(RIFF) 사양의 하위 집합입니다. 이 포맷은 비트스트림에 압축을 적용하지 않으며 다양한 샘플링 레이트와 비트레이트로 오디오 녹음을 저장합니다. 오디오 CD의 표준 포맷 중 하나로 오랫동안 사용되어 왔습니다. 이 파일 형식에 대해 자세히 알아보려면  [here][] .


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


파일 유형 이름 예: "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


파일명 접미사(점 "." 포함) 예: ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


파일 확장자를 파일 유형에 매핑합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 확장자 | java.lang.String | 파일 확장자(마침표 "." 포함). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


지원되는 파일 유형을 검색합니다.

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - 지원되는 파일 형식의 시퀀스를 반환합니다
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


현재 [FileType](../../com.groupdocs.merger.domain/filetype)가 지정된 [FileType](../../com.groupdocs.merger.domain/filetype) 객체와 동일한지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | 현재 [FileType](../../com.groupdocs.merger.domain/filetype) 객체와 비교할 객체입니다. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

if

```
obj
```

매개변수가 [FileType](../../com.groupdocs.merger.domain/filetype)이며 현재 [FileType](../../com.groupdocs.merger.domain/filetype) 객체와 동일한 경우; 그렇지 않으면,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


현재 [FileType](../../com.groupdocs.merger.domain/filetype) 객체의 해시 코드를 반환합니다.

**Returns:**
int - 현재 [FileType](../../com.groupdocs.merger.domain/filetype) 객체에 대한 해시 코드입니다.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


두 [FileType](../../com.groupdocs.merger.domain/filetype) 객체가 동일한지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | 왼쪽 [FileType](../../com.groupdocs.merger.domain/filetype) 객체. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | 오른쪽 [FileType](../../com.groupdocs.merger.domain/filetype) 객체. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### op_Inequality(FileType left, FileType right) {#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Inequality(FileType left, FileType right)
```


Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are not the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Left [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Right [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

두 [FileType](../../com.groupdocs.merger.domain/filetype) 객체가 동일하지 않은 경우; 그렇지 않으면,

```
false
```
### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 현재 객체를 나타내는 문자열입니다.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 기본 텍스트 형식인지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 해당 [FileType](../../com.groupdocs.merger.domain/filetype) 객체. |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format; otherwise,

```
false
```
### isArchive(FileType fileType) {#isArchive-com.groupdocs.merger.domain.FileType-}
```
public static boolean isArchive(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is archive format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 아카이브 형식인 경우; 그렇지 않으면,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 기본 텍스트 형식인지 확인합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 해당 [FileType](../../com.groupdocs.merger.domain/filetype) 객체. |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive image format; otherwise,

```
false
```
### isAudio(FileType fileType) {#isAudio-com.groupdocs.merger.domain.FileType-}
```
public static boolean isAudio(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is audio format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

입력 [FileType](../../com.groupdocs.merger.domain/filetype)이 오디오 형식인 경우; 그렇지 않으면,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
