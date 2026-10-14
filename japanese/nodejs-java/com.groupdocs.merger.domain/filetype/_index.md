---
title: "FileType"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ファイルタイプを表します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

ファイルタイプを表します。**GroupDocs.Merger** がサポートするすべてのファイルタイプのリストを取得したり、拡張子でファイルタイプを検出したりするメソッドを提供します。

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Fields

| Field | 説明 |
| --- | --- |
| [Unknown](#Unknown) | 不明なファイルタイプを表します。 |
| [ZIP](#ZIP) | 圧縮ファイル (.zip) |
| [SevenZ](#SevenZ) | 7-Zip 圧縮ファイル (.7z) |
| [TAR](#TAR) | 統合 Unix ファイルアーカイブ (.tar) |
| [RAR](#RAR) | Roshal ARchive 圧縮ファイル (.rar) |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) は、Microsoft Visio 2013 以降で作成された描画ステンシルです。 |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。 |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) は、マクロに対応した Microsoft Visio アプリケーションで作成された描画ファイルです。 |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された描画テンプレートファイルです。 |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) は、マクロに対応した Microsoft Visio で作成されたテンプレートファイルです。 |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) は、マクロに対応した Microsoft Visio ステンシル ファイルです。 |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) は、Microsoft Visio で図表を作成する際に使用される、描画やシェイプで構成されたステンシルを指します。 |
| [VTX](#VTX) | Visio Template XML File (.vtx) は、XML ファイル形式でディスクに保存される Microsoft Visio の描画テンプレートです。 |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) は、Microsoft Visio で作成された描画またはチャートですが、XML 形式で保存され、拡張子は .VDX です。 |
| [EPUB](#EPUB) | Open eBook File (.epub) は、出版社と読者向けに標準的なデジタル出版形式を提供する電子書籍ファイル形式です。 |
| [BMP](#BMP) | Bitmap Image File (.bmp) は、ビットマップ画像を保存するために使用されるファイルを表します。 |
| [JPG](#JPG) | JPEG 画像 (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) は、非可逆圧縮方式で保存される画像形式の一種です。 |
| [PNG](#PNG) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスタ画像ファイル形式の一種です。 |
| [PS](#PS) | PostScript ファイル (.ps) |
| [TIF](#TIF) | Tagged Image File (.tif) |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format ファイル (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics ファイル (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics 圧縮ファイル (.svgz) |
| [EMF](#EMF) | Windows 拡張メタファイル (.emf) |
| [EMZ](#EMZ) | Windows 圧縮拡張メタファイル (.emz) |
| [HTML](#HTML) | Hypertext Markup Language ファイル (.html) は、ブラウザで表示するために作成されたウェブページの拡張子です。 |
| [MHT](#MHT) | MHTML Web アーカイブ (.mht) は、さまざまなアプリケーションで作成できるウェブページのアーカイブ形式です。 |
| [MHTML](#MHTML) | MIME HTML ファイル (.mhtml) は、さまざまなアプリケーションで作成できるウェブページのアーカイブ形式です。 |
| [ONE](#ONE) | OneNote ドキュメント (.one) ファイルは、Microsoft OneNote アプリケーションで作成されます。 |
| [PDF](#PDF) | Portable Document Format ファイル (.pdf) は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準として導入されたファイル形式です。 |
| [XPS](#XPS) | XML Paper Specification ファイル (.xps) は、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。 |
| [TEX](#TEX) | LaTeX ソースドキュメント (.tex) は、プログラミング機能とマークアップ機能を備えた言語で、文書の組版に使用されます。 |
| [PPT](#PPT) | PowerPoint プレゼンテーション (.ppt) は、スライドショーとして表示するためのスライドのコレクションで構成された PowerPoint ファイルを表します。 |
| [PPTX](#PPTX) | PowerPoint Open XML プレゼンテーション (.pptx) は、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。 |
| [PPS](#PPS) | PowerPoint スライドショー (.pps) は、スライドショー目的で Microsoft PowerPoint を使用して作成されたファイルです。 |
| [PPSX](#PPSX) | PowerPoint Open XML スライドショー (.ppsx) は、Microsoft PowerPoint 2007 以降を使用してスライドショー目的で作成されたファイルです。 |
| [ODP](#ODP) | OpenDocument プレゼンテーション (.odp) は、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーションファイル形式を表します。 |
| [OTP](#OTP) | OpenDocument プレゼンテーションテンプレート (.otp) は、OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーションテンプレートファイルを表します。 |
| [XLS](#XLS) | Excel スプレッドシート (.xls) は、Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシートプログラムでも作成できるファイルです。 |
| [XLSX](#XLSX) | Microsoft Excel Open XML スプレッドシート (.xlsx) は、Microsoft Office 2007 のリリースとともに Microsoft が導入した、Microsoft Excel ドキュメントのよく知られた形式です。 |
| [XLSM](#XLSM) | Excel Open XML マクロ有効スプレッドシート (.xlsm) は、マクロをサポートするスプレッドシートファイルの一種です。 |
| [XLSB](#XLSB) | Excel バイナリスプレッドシート (.xlsb) ファイル形式は、Excel ブックの内容を指定するレコードと構造の集合である Excel バイナリファイル形式を定義しています。 |
| [CSV](#CSV) | カンマ区切り値ファイル (.csv) は、カンマで区切られた値を持つデータレコードを含むプレーンテキストファイルを表します。 |
| [TSV](#TSV) | タブ区切り値ファイル (.tsv) は、タブで区切られたデータをプレーンテキスト形式で表します。 |
| [ODS](#ODS) | OpenDocument スプレッドシート (.ods)。 |
| [XLTM](#XLTM) | Excel Open XML マクロ有効スプレッドシートテンプレート (.xltm) は、Microsoft Excel がマクロ有効テンプレートファイルとして生成するファイルを表します。 |
| [XLTX](#XLTX) | Excel Open XML スプレッドシートテンプレート (.xltx) ファイルは、Office OpenXML ファイル形式仕様に基づいています。 |
| [XLT](#XLT) | Excel テンプレートファイル (.xlt) は、Microsoft Office スイートの一部として提供されるスプレッドシートアプリケーション Microsoft Excel で作成されたテンプレートファイルです。 |
| [XLAM](#XLAM) | Excel マクロ有効アドイン (.xlam)。 |
| [DOC](#DOC) | Microsoft Word ドキュメント (.doc) は、Microsoft Word またはその他のワードプロセッサで生成されたバイナリファイル形式の文書を表します。 |
| [DOCX](#DOCX) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word 文書のよく知られた形式です。 |
| [DOCM](#DOCM) | Word Open XML マクロ有効ドキュメント (.docm) ファイルは、Microsoft Word 2007 以降で生成され、マクロを実行できる文書です。 |
| [DOT](#DOT) | Word ドキュメントテンプレート (.dot) ファイルは、Microsoft Word が作成したテンプレートで、今後の DOC または DOCX ファイル生成のために事前に書式設定された設定を持ちます。 |
| [DOTX](#DOTX) | Word Open XML ドキュメントテンプレート (.dotx) は、Microsoft Word が作成したテンプレートで、今後の DOCX ファイル生成のために事前に書式設定された設定を持ちます。 |
| [DOTM](#DOTM) | Word Open XML マクロ有効ドキュメントテンプレート (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。 |
| [RTF](#RTF) | リッチテキスト形式ファイル (.rtf) は Microsoft によって導入・文書化され、リッチテキスト形式 (RTF) は、アプリケーション内で使用するための書式付きテキストとグラフィックをエンコードする方法を表します。 |
| [TXT](#TXT) | プレーンテキストファイル (.txt) は、行形式のプレーンテキストを含むテキスト文書を表します。 |
| [ERR](#ERR) | エラーログファイル (.err) は、プログラムによって生成されたエラーメッセージを含むテキストファイルです。 |
| [ODT](#ODT) | OpenDocument テキスト文書 (.odt) ファイルは、OpenDocument テキストファイル形式に基づくワードプロセッサアプリケーションで作成された文書の一種です。 |
| [OTT](#OTT) | OpenDocument ドキュメントテンプレート (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されたテンプレート文書を表します。 |
| [WAV](#WAV) | WAV は WAVE（Waveform Audio File Format）として知られ、デジタルオーディオファイルを保存するための Microsoft\u2019s Resource Interchange File Format (RIFF) 仕様のサブセットです。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | ファイルタイプ名（例） |
| [getExtension()](#getExtension--) | ファイル名サフィックス（ピリオド「.」を含む）（例） |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | ファイル拡張子をファイルタイプにマッピングします。 |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | サポートされているファイルタイプを取得します |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | 現在の [FileType](../../com.groupdocs.merger.domain/filetype) が、指定された [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトと同じかどうかを判断します。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 現在の [FileType](../../com.groupdocs.merger.domain/filetype) が、指定されたオブジェクトと同じかどうかを判断します。 |
| [hashCode()](#hashCode--) | 現在の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトのハッシュコードを返します。 |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 2 つの [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトが同じかどうかを判断します。 |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 2 つの [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトが異なるかどうかを判断します。 |
| [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | 入力された [FileType](../../com.groupdocs.merger.domain/filetype) がプリミティブテキスト形式かどうかを判断します。 |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | 入力された [FileType](../../com.groupdocs.merger.domain/filetype) がアーカイブ形式かどうかを判断します。 |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | 入力された [FileType](../../com.groupdocs.merger.domain/filetype) がプリミティブテキスト形式かどうかを判断します。 |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | 入力された [FileType](../../com.groupdocs.merger.domain/filetype) がオーディオ形式かどうかを判断します。 |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


不明なファイルタイプを表します。

### ZIP {#ZIP}
```
public static FileType ZIP
```


圧縮ファイル (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


7-Zip 圧縮ファイル (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


統合 Unix ファイルアーカイブ (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal ARchive 圧縮ファイル (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio ステンシル ファイル (.vssx) は、Microsoft Visio 2013 以降で作成された描画ステンシルです。VSSX ファイル形式は Visio 2013 以降で開くことができます。Visio ファイルは、図形のコレクション、コネクタ、フローチャート、ネットワークレイアウト、UML ダイアグラムなど、さまざまな描画要素の表現で知られています。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。これは、従来のバイナリ形式 .VSD（以前の Microsoft Visio がサポート）に代わるものとして開発されました。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された描画ファイルです。VSDM ファイルは VSDX に似た OPC/XML 描画で、ファイルを開く際にマクロを実行できる機能も提供します。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された描画テンプレートファイルです。これらの VSTX ファイルは、デフォルトのレイアウトと設定で .VSDX ファイルとして保存される Visio 図面作成の出発点を提供します。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレートファイルです。VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) は、マクロのサポートを提供する Microsoft Visio ステンシル ファイルです。VSSM ファイルを開くと、マクロを実行して図中の形状の書式設定や配置を行うことができます。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) は、Microsoft Visio で図表作成に使用される描画や形状からなるステンシルを指します。VSX ファイルは XML 形式で保存され、Visio 2013 までサポートされていました。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) は、XML 形式でディスクに保存される Microsoft Visio の描画テンプレートです。このテンプレートは、同じ設定の Visio ファイルを複数作成するための基本設定を提供することを目的としています。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx) は、Microsoft Visio で作成された描画またはチャートですが、.VDX 拡張子の XML 形式で保存されます。Visio の描画 XML ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) は、出版社と読者向けに標準的なデジタル出版形式を提供する電子書籍ファイル形式です。この形式は現在非常に一般的で、多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) は、ビットマップデジタル画像を保存するために使用されるファイルを表します。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG 画像 (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) は、非可逆圧縮方式で保存される画像形式の一種です。圧縮の結果として得られる画像は、保存サイズと画質のバランスを取ったものになります。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスタ画像ファイル形式の一種です。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript ファイル (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Tagged Image File (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Tagged Image File Format (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Graphical Interchange Format ファイル (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Scalable Vector Graphics ファイル (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Scalable Vector Graphics 圧縮ファイル (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Windows 拡張メタファイル (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows 圧縮拡張メタファイル (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) は、ブラウザで表示されるウェブページの拡張子です。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) は、さまざまなアプリケーションで作成できるウェブページのアーカイブ形式です。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) は、さまざまなアプリケーションで作成できるウェブページのアーカイブ形式です。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Document (.one) ファイルは、Microsoft OneNote アプリケーションで作成されます。OneNote は、メモ帳のように情報を収集できるようにします。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で文書や参考資料を表現する標準として導入されたファイル形式です。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) は、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) は、プログラミング機能とマークアップ機能を備えた言語で、文書の組版に使用されます。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation (.ppt) は、スライドショーとして表示されるスライドのコレクションで構成された PowerPoint ファイルを表します。これは、Microsoft PowerPoint 97-2003 で使用されるバイナリファイル形式を指定しています。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation (.pptx) は、人気のある Microsoft PowerPoint アプリケーションで作成されたプレゼンテーションファイルです。従来のバイナリ形式 PPT と異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーションファイル形式に基づいています。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show (.pps) は、スライドショー目的で Microsoft PowerPoint を使用して作成されたファイルです。PPS ファイルの読み取りと作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slide Show (.ppsx) は、Microsoft PowerPoint 2007 以降でスライドショー目的に作成されたファイルです。このファイル形式の詳細は [here][] をご覧ください。


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp) は、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーション ファイル形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) は、OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーション テンプレート ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) は、Microsoft Excel や OpenOffice Calc、Apple Numbers などの類似スプレッドシート プログラムで作成できるファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) は、Microsoft が Office 2007 のリリースとともに導入した、Microsoft Excel ドキュメント用の広く知られた形式です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) ファイル形式は、Excel バイナリ ファイル形式を指定し、Excel ワークブックの内容を示すレコードと構造の集合です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) は、カンマ区切りの値でデータレコードを含むプレーンテキスト ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) は、タブで区切られたデータを含むプレーンテキスト形式のファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument スプレッドシート (.ods)。

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) は、Microsoft Excel がマクロ対応テンプレート ファイルとして生成するファイルを表します。XLTM ファイルは構造上 XLTX と似ていますが、後者はマクロ付きテンプレートの作成をサポートしません。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) ファイルは、Office OpenXML ファイル形式仕様に基づいています。これは、XLTX ファイルで指定された設定と同じ設定を持つ XLSX ファイルを生成するために使用できる標準テンプレート ファイルを作成するために使用されます。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt) は、Microsoft Office スイートの一部であるスプレッドシート アプリケーション Microsoft Excel で作成されたテンプレート ファイルです。Microsoft Office 97-2003 は新しい XLT ファイルの作成と開くことをサポートしていました。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel マクロ有効アドイン (.xlam)。

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) は、Microsoft Word やその他のワードプロセッサで生成されるバイナリ ファイル形式のドキュメントを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) は、Microsoft Word ドキュメント用の広く知られた形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、この新しいドキュメント形式の構造はプレーンバイナリから XML とバイナリ ファイルの組み合わせに変更されました。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) ファイルは、Microsoft Word 2007 以降で生成され、マクロを実行できるドキュメントです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) ファイルは、Microsoft Word が作成し、今後の DOC または DOCX ファイル生成のために事前に書式設定された設定を持つテンプレート ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) は、Microsoft Word が作成し、今後の DOCX ファイル生成のために事前に書式設定された設定を持つテンプレート ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf) は Microsoft によって導入・文書化されたリッチテキスト形式 (RTF) で、アプリケーション内で使用するための書式付きテキストとグラフィックをエンコードする方法を表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt) は、行単位のプレーンテキストを含むテキスト ドキュメントを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Error Log File (.err) は、プログラムが生成したエラーメッセージを含むテキスト ファイルです。このファイル形式の詳細は [here][] で確認してください。


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) ファイルは、OpenDocument テキスト ファイル形式に基づくワードプロセッシング アプリケーションで作成されたドキュメントの一種です。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションが生成するテンプレート ドキュメントを表します。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV（WAVE、Waveform Audio File Format の略称）は、Microsoft のリソース インターチェンジ ファイル形式（RIFF）仕様のサブセットで、デジタルオーディオ ファイルを保存するためのものです。この形式はビットストリームに圧縮を施さず、異なるサンプリングレートとビットレートで音声を記録します。オーディオ CD の標準フォーマットの一つとして長らく使用されています。このファイル形式の詳細は [here][] で確認してください。


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


ファイルタイプ名（例: "Microsoft Word Document"）。

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


ファイル名のサフィックス（ピリオド "." を含む）例: ".doc"。

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


ファイル拡張子をファイルタイプにマッピングします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 拡張子 | java.lang.String | ファイル拡張子（ピリオド「.」を含む）。 |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


サポートされているファイルタイプを取得します

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - サポートされているファイルタイプのシーケンスを返します
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


現在の [FileType](../../com.groupdocs.merger.domain/filetype) が、指定された [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトと同じかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | 現在の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトと比較するオブジェクトです。 |

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

パラメータが [FileType](../../com.groupdocs.merger.domain/filetype) であり、現在の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトと同じ場合; それ以外の場合、

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


現在の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトのハッシュコードを返します。

**Returns:**
int - 現在の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトのハッシュコードです。
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


2 つの [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトが同じかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | 左側の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトです。 |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | 右側の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトです。 |

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

両方の [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトが同じでない場合; それ以外の場合、

```
false
```
### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。

**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列です。
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


入力された [FileType](../../com.groupdocs.merger.domain/filetype) がプリミティブテキスト形式かどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | この [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトです。 |

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

入力の [FileType](../../com.groupdocs.merger.domain/filetype) がアーカイブ形式の場合; それ以外の場合、

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


入力された [FileType](../../com.groupdocs.merger.domain/filetype) がプリミティブテキスト形式かどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | この [FileType](../../com.groupdocs.merger.domain/filetype) オブジェクトです。 |

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

入力の [FileType](../../com.groupdocs.merger.domain/filetype) がオーディオ形式の場合; それ以外の場合、

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
