---
title: "FileType"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "ファイルタイプを表します。GroupDocs.Merger がサポートするすべてのファイルタイプの一覧を取得したり、拡張子でファイルタイプを検出するメソッドを提供します。"
type: docs
weight: 110
url: /ja/net/groupdocs.merger.domain/filetype/
---
## FileType class

ファイルタイプを表します。**GroupDocs.Merger** がサポートするすべてのファイルタイプの一覧を取得したり、拡張子でファイルタイプを検出したりするメソッドを提供します。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | ファイル名のサフィックス（ピリオド「.」を含む）例: ".doc"。 |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | ファイルタイプ名 例: "Microsoft Word Document"。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | ファイル拡張子をファイルタイプにマッピングします。 |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | 現在の[`FileType`](../filetype) が指定された[`FileType`](../filetype) オブジェクトと同じかどうかを判定します。 |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | 現在の[`FileType`](../filetype) が指定されたオブジェクトと同じかどうかを判定します。 |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | 現在の[`FileType`](../filetype) オブジェクトのハッシュコードを返します。 |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | サポートされているファイルタイプを取得します |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | 入力された[`FileType`](../filetype) がアーカイブ形式かどうかを判定します。 |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | 入力された[`FileType`](../filetype) がオーディオ形式かどうかを判定します。 |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | 入力された[`FileType`](../filetype) が画像形式かどうかを判定します。 |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | 入力された[`FileType`](../filetype) がプレーンテキスト形式かどうかを判定します。 |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | 2つの[`FileType`](../filetype) オブジェクトが同じかどうかを判定します。 |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | 2つの[`FileType`](../filetype) オブジェクトが異なるかどうかを判定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap Image File（.bmp）は、ビットマップデジタル画像を保存するために使用されるファイルを表します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/bmp)をご覧ください。 |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 圧縮ファイル（.bz2） |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | Comma Separated Values File（.csv）は、カンマ区切りの値でデータレコードを含むプレーンテキストファイルを表します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/csv)をご覧ください。 |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word Document（.doc）は、Microsoft Word または他のワードプロセッサで生成されたバイナリ形式の文書を表します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/word-processing/doc)をご覧ください。 |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML マクロ有効ドキュメント (.docm) ファイルは、Microsoft Word 2007 以降で作成された、マクロを実行できるドキュメントです。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/docm)です。 |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word 文書で広く知られている形式です。2007 年に Microsoft Office 2007 がリリースされた際に導入され、この新しいドキュメント形式の構造は従来のバイナリから XML とバイナリ ファイルの組み合わせに変更されました。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/docx)です。 |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | Word 文書テンプレート (.dot) ファイルは、Microsoft Word が作成したテンプレートで、今後生成される DOC または DOCX ファイルのために事前に書式設定された設定を保持します。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/dot)です。 |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML マクロ有効ドキュメントテンプレート (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレートファイルを表します。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/dotm)です。 |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML ドキュメントテンプレート (.dotx) は、Microsoft Word が作成したテンプレートで、今後生成される DOCX ファイルのために事前に書式設定された設定を保持します。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/dotx)です。 |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows 拡張メタファイル (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows 圧縮拡張メタファイル (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook ファイル (.epub) は、出版社と読者向けに標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。このフォーマットは現在非常に一般的で、多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。このファイル形式の詳細は[here](https://docs.fileformat.com/ebook/epub)です。 |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | エラーログファイル (.err) は、プログラムによって生成されたエラーメッセージを含むテキストファイルです。このファイル形式の詳細は[here](https://fileinfo.com/extension/err)です。 |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | Graphics Interchange Format ファイル (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip 圧縮ファイル (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language ファイル (.html) は、ブラウザで表示されるウェブページの拡張子です。このファイル形式の詳細は[here](https://docs.fileformat.com/web/html)です。 |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG 画像 (.jpeg) は、非可逆圧縮方式で保存される画像フォーマットの一種です。圧縮の結果として得られる画像は、保存サイズと画質のバランスを取ったものです。このファイル形式の詳細は[here](https://docs.fileformat.com/image/jpeg)です。 |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG 画像 (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web アーカイブ (.mht) は、さまざまなアプリケーションで作成できるウェブページアーカイブ形式です。このファイル形式の詳細は[here](https://docs.fileformat.com/web/mhtml)です。 |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML ファイル (.mhtml) は、さまざまなアプリケーションで作成できるウェブページアーカイブ形式です。このファイル形式の詳細は[here](https://docs.fileformat.com/web/mhtml)です。 |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | 拡張子 .mp3 のファイルは、MPEG-1 Audio Layer III または MPEG-2 Audio Layer III に基づくデジタルエンコードされた音声ファイル形式です。これは、Moving Picture Experts Group (MPEG) によって開発されたレイヤー3音声圧縮を使用しています。MP3 ファイル形式で実現される圧縮率は、.WAV や .AIF ファイルの約 1/10 のサイズです。このファイル形式の詳細は[here](https://docs.fileformat.com/audio/mp3)です。 |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument プレゼンテーション (.odp) は、OpenOffice.org が OASIS Open 標準で使用するプレゼンテーションファイル形式を表します。このファイル形式の詳細は[here](https://docs.fileformat.com/presentation/odp)です。 |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument スプレッドシート (.ods) このファイル形式の詳細は[here](https://docs.fileformat.com/spreadsheet/ods)です。 |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument テキストドキュメント (.odt) ファイルは、OpenDocument テキストファイル形式に基づくワードプロセッシングアプリケーションで作成される文書の一種です。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/odt)です。 |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote ドキュメント (.one) ファイルは、Microsoft OneNote アプリケーションで作成されます。OneNote は、ノートを取るための下書き用紙のように情報を収集できるようにします。このファイル形式の詳細は[here](https://docs.fileformat.com/note-taking/one)です。 |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument プレゼンテーションテンプレート (.otp) は、OASIS OpenDocument 標準形式でアプリケーションが作成するプレゼンテーションテンプレートファイルを表します。このファイル形式の詳細は[here](https://docs.fileformat.com/presentation/otp)です。 |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument ドキュメントテンプレート (.ott) は、OASIS の OpenDocument 標準に準拠したアプリケーションが生成するテンプレート文書を表します。このファイル形式の詳細は[here](https://docs.fileformat.com/word-processing/ott)です。 |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format ファイル (.pdf) は、アプリケーションソフトウェア、ハードウェア、オペレーティングシステムに依存しない形式で文書やその他の参照資料を表現する標準として導入されたファイル形式です。このファイル形式の詳細は[here](https://docs.fileformat.com/view/pdf)です。 |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスター画像ファイル形式の一種です。このファイル形式の詳細は[here](https://docs.fileformat.com/image/png)です。 |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML マクロ有効プレゼンテーションテンプレート (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML プレゼンテーションテンプレート (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) は、Microsoft PowerPoint を使用してスライドショー目的で作成されたファイルです。PPS ファイルの読み取りと作成は Microsoft PowerPoint 97-2003 でサポートされています。このファイル形式の詳細は、[here](https://docs.fileformat.com/presentation/pps) でご確認ください。 |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML マクロ有効スライド (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) は、Microsoft PowerPoint 2007 以降を使用してスライドショー目的で作成されたファイルです。このファイル形式の詳細は、[here](https://docs.fileformat.com/presentation/ppsx) でご確認ください。 |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) は、スライドショーとして表示するためのスライドのコレクションで構成された PowerPoint ファイルを表します。これは Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定しています。このファイル形式の詳細は、[here](https://docs.fileformat.com/presentation/ppt) でご確認ください。 |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML マクロ有効プレゼンテーション |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) は、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。従来のバイナリ形式であった PPT 形式とは異なり、PPTX 形式は Microsoft PowerPoint のオープン XML プレゼンテーション ファイル形式に基づいています。このファイル形式の詳細は、[here](https://docs.fileformat.com/presentation/pptx) でご確認ください。 |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript ファイル (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive 圧縮ファイル (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) は Microsoft によって導入・文書化されたリッチテキスト形式（RTF）で、フォーマットされたテキストとグラフィックをアプリケーション内で使用するためのエンコード方法を表します。このファイル形式の詳細は、[here](https://docs.fileformat.com/word-processing/rtf) でご確認ください。 |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip 圧縮ファイル (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Scalable Vector Graphics ファイル (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Scalable Vector Graphics 圧縮ファイル (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | 統合 Unix ファイルアーカイブ (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX ソースドキュメント (.tex) は、プログラミング機能とマークアップ機能を備えた言語で、文書の組版に使用されます。このファイル形式の詳細は、[here](https://docs.fileformat.com/page-description-language/tex) でご確認ください。 |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | タグ付き画像ファイル (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | タグ付き画像ファイル形式 (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tab Separated Values File (.tsv) は、タブで区切られたプレーンテキスト形式のデータを表します。このファイル形式の詳細は、[here](https://docs.fileformat.com/spreadsheet/tsv) でご確認ください。 |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) は、行単位のプレーンテキストを含むテキストドキュメントを表します。このファイル形式の詳細は、[here](https://docs.fileformat.com/word-processing/txt) でご確認ください。 |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | 不明なファイルタイプを表します。 |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) は、Microsoft Visio で作成された図やチャートですが、XML 形式で保存され、拡張子は .VDX です。Visio の描画 XML ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。このファイル形式の詳細は、[here](https://docs.fileformat.com/image/vdx) でご確認ください。 |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | Visio 描画ファイル (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された描画ファイルです。VSDM ファイルは VSDX と類似した OPC/XML 描画で、ファイルを開く際にマクロを実行できる機能も提供します。このファイル形式の詳細は、[here](https://docs.fileformat.com/image/vsdm) でご確認ください。 |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio のファイル形式を表します。これは、従来のバイナリ形式 .VSD（以前のバージョンの Microsoft Visio がサポート）に代わるものとして開発されました。このファイル形式の詳細は、[here](https://docs.fileformat.com/image/vsdx) でご確認ください。 |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | Visio ステンシル ファイル(.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio マクロ対応ステンシル ファイル (.vssm) は、マクロをサポートする Microsoft Visio ステンシル ファイルです。VSSM ファイルを開くと、マクロを実行して図中の形状の書式設定や配置を希望通りに行うことができます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/vssm)をご覧ください。 |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio ステンシル ファイル (.vssx) は、Microsoft Visio 2013 以降で作成された描画ステンシルです。VSSX ファイル形式は Visio 2013 以降で開くことができます。Visio ファイルは、図形のコレクション、コネクタ、フローチャート、ネットワークレイアウト、UML 図など、さまざまな描画要素を表現できることで知られています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/vssx)をご覧ください。 |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Visio 描画テンプレート (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio マクロ対応描画テンプレート (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレート ファイルです。VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/vstm)をご覧ください。 |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio 描画テンプレート (.vstx) は、Microsoft Visio 2013 以降で作成された描画テンプレート ファイルです。これらの VSTX ファイルは、デフォルトのレイアウトと設定を持つ .VSDX ファイルとして保存される Visio 図面を作成するための出発点を提供します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/vstx)をご覧ください。 |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio ステンシル XML ファイル (.vsx) は、Microsoft Visio で図表を作成する際に使用される描画や図形で構成されたステンシルを指します。VSX ファイルは XML 形式で保存され、Visio 2013 までサポートされていました。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/vsx)をご覧ください。 |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio テンプレート XML ファイル (.vtx) は、XML 形式でディスクに保存される Microsoft Visio の描画テンプレートです。このテンプレートは、同じ設定を持つ複数の Visio ファイルを作成するための基本設定を提供することを目的としています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/image/vtx)をご覧ください。 |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV は、WAVE（Waveform Audio File Format）として知られ、デジタル音声ファイルを保存するための Microsoft の Resource Interchange File Format（RIFF）仕様のサブセットです。この形式はビットストリームに圧縮を施さず、さまざまなサンプリングレートやビットレートで音声を保存します。オーディオ CD の標準フォーマットの一つとして長らく使用されています。このファイル形式の詳細は[こちら](https://docs.fileformat.com/audio/wav)をご覧ください。 |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel マクロ対応アドイン (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel スプレッドシート (.xls) は、Microsoft Excel のほか、OpenOffice Calc や Apple Numbers などの類似スプレッドシート プログラムでも作成できるファイルです。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xls)をご覧ください。 |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel バイナリ スプレッドシート (.xlsb) ファイル形式は、Excel バイナリ ファイル形式を指定し、Excel ブックの内容を表すレコードや構造の集合です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xlsb)をご覧ください。 |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML マクロ対応スプレッドシート (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xlsm)をご覧ください。 |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML スプレッドシート (.xlsx) は、Microsoft が Microsoft Office 2007 のリリースとともに導入した、広く知られた Excel ドキュメント形式です。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xlsx)をご覧ください。 |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel テンプレート ファイル (.xlt) は、Microsoft Office スイートに含まれるスプレッドシート アプリケーション Microsoft Excel で作成されたテンプレート ファイルです。Microsoft Office 97-2003 では新規 XLT ファイルの作成と開くことがサポートされていました。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xlt)をご覧ください。 |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML マクロ対応スプレッドシート テンプレート (.xltm) は、Microsoft Excel が生成するマクロ対応テンプレート ファイルを表します。XLTM ファイルは構造上 XLTX と似ていますが、後者はマクロ付きテンプレートの作成をサポートしていません。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xltm)をご覧ください。 |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML スプレッドシート テンプレート (.xltx) ファイルは、Office OpenXML ファイル形式仕様に基づいています。これは、XLTX ファイルで指定された設定と同じ設定を持つ XLSX ファイルを生成するために使用できる標準的なテンプレート ファイルを作成するために利用されます。このファイル形式の詳細は[こちら](https://docs.fileformat.com/spreadsheet/xltx)をご覧ください。 |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification ファイル (.xps) は、Microsoft が作成した XML Paper Specification に基づくページレイアウト ファイルを表します。このファイル形式の詳細は[こちら](https://docs.fileformat.com/page-description-language/xps)をご覧ください。 |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | 圧縮ファイル (.zip) |

### 備考

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### 関連項目

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
