---
title: FileType
second_title: GroupDocs.Merger for .NET API リファレンス
description: ファイルの種類を表しますでサポートされているすべてのファイル タイプのリストを取得するメソッドを提供しますGroupDocs.Merger  拡張子でファイルタイプを検出 etc.
type: docs
weight: 100
url: /ja/net/groupdocs.merger.domain/filetype/
---
## FileType class

ファイルの種類を表します。でサポートされているすべてのファイル タイプのリストを取得するメソッドを提供します。**GroupDocs.Merger** , 拡張子でファイルタイプを検出 etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | ファイル名のサフィックス (ピリオド "." を含む) 例: ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | ファイルの種類名 (例: "Microsoft Word ドキュメント". |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | ファイル拡張子をファイル タイプにマップします。 |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | 現在の[`FileType`](../filetype)指定と同じです[`FileType`](../filetype)object. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | 現在の[`FileType`](../filetype)指定されたオブジェクトと同じです. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | 現在のハッシュ コードを返します。[`FileType`](../filetype)object. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | 現在のオブジェクトを表す文字列を返します。 |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | サポートされているファイル タイプを取得します |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | 入力かどうかを決定します[`FileType`](../filetype)アーカイブ形式です. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | 入力かどうかを決定します[`FileType`](../filetype)画像形式です. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | 入力かどうかを決定します[`FileType`](../filetype)プリミティブ テキスト形式です。 |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | 2 つの[`FileType`](../filetype)オブジェクトは同じです. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | 2 つの[`FileType`](../filetype)オブジェクトは同じではありません. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | ビットマップ イメージ ファイル (.bmp) は、ビットマップ デジタル イメージの保存に使用されるファイルを表します。このファイル形式の詳細[ここ](https://docs.fileformat.com/image/bmp) |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 圧縮ファイル (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | カンマ区切り値ファイル (.csv) は、カンマ区切りの値を持つデータのレコードを含むプレーン テキスト ファイルを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/csv) |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word ドキュメント (.doc) は、Microsoft Word またはその他のワード プロセッシング ドキュメントによって生成されたドキュメントをバイナリ ファイル形式で表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/doc) |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML マクロ有効ドキュメント (.docm) ファイルは、マクロを実行できる Microsoft Word 2007 以降で生成されたドキュメントです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/docm) |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML ドキュメント (.docx) は、Microsoft Word ドキュメントのよく知られた形式です。 2007 年の Microsoft Office 2007 のリリースで導入されたこの新しいドキュメント形式の構造は、プレーン バイナリから XML ファイルとバイナリ ファイルの組み合わせに変更されました。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/docx) |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word ドキュメント テンプレート (.dot) ファイルは、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOC または DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/dot) |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML マクロ有効ドキュメント テンプレート (.dotm) は、Microsoft Word 2007 以降で作成されたテンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/dotm) |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML ドキュメント テンプレート (.dotx) は、Microsoft Word によって作成されたテンプレート ファイルで、さらに DOCX ファイルを生成するための設定が事前にフォーマットされています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/dotx) |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook ファイル (.epub) は、出版社と消費者に標準のデジタル出版物形式を提供する電子書籍ファイル形式です。この形式は現在非常に一般的であるため、多くの電子書籍リーダーやソフトウェア アプリケーションでサポートされています. このファイル形式の詳細[ここ](https://docs.fileformat.com/ebook/epub) |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | エラー ログ ファイル (.err) は、プログラムによって生成されたエラー メッセージを含むテキスト ファイルです。 このファイル形式の詳細[ここ](https://fileinfo.com/extension/err) |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | グラフィカル インターチェンジ フォーマット ファイル (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip 圧縮ファイル (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | ハイパーテキスト マークアップ言語ファイル (.html) は、ブラウザーで表示するために作成された Web ページの拡張子です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/web/html) |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG 画像 (.jpeg) は、非可逆圧縮方式を使用して保存される画像形式の一種です。圧縮の結果としての出力画像は、ストレージ サイズと画質のトレードオフになります。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/jpeg) |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG 画像 (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web アーカイブ (.mht) は、さまざまなアプリケーションで作成できる Web ページ アーカイブ形式です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/web/mhtml) |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML ファイル (.mhtml) は、さまざまなアプリケーションで作成できる Web ページ アーカイブ形式です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/web/mhtml) |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument プレゼンテーション (.odp) は、OASISOpen 標準で OpenOffice.org が使用するプレゼンテーション ファイル形式を表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/presentation/odp) |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument スプレッドシート (.ods) このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/ods) |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument テキスト ドキュメント (.odt) ファイルは、OpenDocument テキスト ファイル形式に基づくワープロ アプリケーションで作成されたドキュメントのタイプです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/odt) |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote ドキュメント (.one) ファイルは、Microsoft OneNote アプリケーションによって作成されます。 OneNote を使用すると、下書き帳を使用してメモを取っているかのように、アプリケーションを使用して情報を収集できます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/note-taking/one) |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument プレゼンテーション テンプレート (.otp) は、OASIS OpenDocument 標準形式のアプリケーションによって作成されたプレゼンテーション テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/presentation/otp) |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument ドキュメント テンプレート (.ott) は、OASIS の OpenDocument 標準形式に準拠したアプリケーションによって生成されたテンプレート ドキュメントを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/ott) |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) は、アプリケーション ソフトウェア、ハードウェア、およびオペレーティング システムに依存しない形式でドキュメントやその他の参考資料を表現するための標準として導入されたファイル形式です。 このファイルの詳細フォーマット[ここ](https://docs.fileformat.com/view/pdf) |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) は、ロスレス圧縮を使用するラスター イメージ ファイル形式の一種です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/png) |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint スライド ショー (.pps) は、Microsoft PowerPoint を使用してスライド ショー用に作成されたファイルです。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/presentation/pps) |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML スライド ショー (.ppsx) は、スライド ショー用に Microsoft PowerPoint 2007 以降を使用して作成されたファイルです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/presentation/ppsx) |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint プレゼンテーション (.ppt) は、スライドショーとして表示するスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/presentation/ppt). |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML プレゼンテーション (.pptx) は、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。バイナリであった以前のバージョンのプレゼンテーション ファイル形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint オープン XML プレゼンテーション ファイル形式に基づいています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/presentation/pptx) |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript ファイル (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive 圧縮ファイル (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Microsoft によって導入および文書化されたリッチ テキスト フォーマット ファイル (.rtf)。リッチ テキスト フォーマット (RTF) は、アプリケーション内で使用するために書式設定されたテキストおよびグラフィックをエンコードする方法を表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/rtf) |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip 圧縮ファイル (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | 統合された Unix ファイル アーカイブ (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX ソース ドキュメント (.tex) は、プログラミング機能とマークアップ機能で構成される言語で、ドキュメントのタイプセットに使用されます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/page-description-language/tex) |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | タグ付き画像ファイル (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | タグ付き画像ファイル形式 (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | タブ区切り値ファイル (.tsv) は、プレーン テキスト形式のタブで区切られたデータを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/tsv) |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | プレーン テキスト ファイル (.txt) は、行形式のプレーン テキストを含むテキスト ドキュメントを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/word-processing/txt) |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | 不明なファイル タイプを表します。 |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio 図面 XML ファイル (.vdx) は、Microsoft Visio で作成された図面またはグラフですが、XML 形式で保存すると .VDX 拡張子が付きます。 Visio 図面 XML ファイルは、Microsoft が開発した Visio ソフトウェアで作成されます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vdx). |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio マクロ対応図面 (.vsdm) は、マクロをサポートする Microsoft Visio アプリケーションで作成された図面ファイルです。 VSDM ファイルは、VSDX に似た OPC/XML 図面ですが、ファイルを開いたときにマクロを実行する機能も提供します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vsdm). |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) は、Microsoft Office 2013 以降で導入された Microsoft Visio ファイル形式を表します。これは、以前のバージョンの Microsoft Visio でサポートされていたバイナリ ファイル形式 .VSD を置き換えるために開発されました。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vsdx). |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio マクロ対応ステンシル ファイル (.vssm) は、マクロをサポートする Microsoft Visio ステンシル ファイルです。 VSSM ファイルを開くと、マクロを実行して、ダイアグラム内の図形の目的の書式設定と配置を実現できます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vssm). |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio ステンシル ファイル (.vssx) は、Microsoft Visio 2013 以降で作成された図面ステンシルです。 VSSX ファイル形式は、Visio 2013 以降で開くことができます。 Visio ファイルは、図形のコレクション、コネクタ、フローチャート、ネットワーク レイアウト、UML ダイアグラム、 など、さまざまな描画要素の表現で知られています。このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vssx). |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio マクロ有効図面テンプレート (.vstm) は、マクロをサポートする Microsoft Visio で作成されたテンプレート ファイルです。 VSDX ファイルとは異なり、VSTM テンプレートから作成されたファイルは、Visual Basic for Applications (VBA) コードで開発されたマクロを実行できます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vstm). |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) は、Microsoft Visio 2013 以降で作成された図面テンプレート ファイルです。これらの VSTX ファイルは、既定のレイアウトと設定を使用して、.VSDX ファイルとして保存された Visio 図面を作成するための開始点を提供します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vstx). |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio ステンシル XML ファイル (.vsx) は、Microsoft Visio で図を作成するために使用される図面と図形で構成されるステンシルを指します。 VSX ファイルは XML ファイル形式で保存され、Visio 2013 までサポートされていました。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vsx). |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio テンプレート XML ファイル (.vtx) は、XML ファイル形式でディスクに保存される Microsoft Visio 図面テンプレートです。このテンプレートは、同じ設定の複数の Visio ファイルを作成するために使用できる基本設定を含むファイルを提供することを目的としています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/image/vtx). |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel マクロ有効アドイン (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel スプレッドシート (.xls) は、Microsoft Excel だけでなく、OpenOffice Calc や Apple Numbers などの他の同様のスプレッドシート プログラムでも作成できるファイルです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xls) |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel バイナリ スプレッドシート (.xlsb) ファイル形式は、Excel ブックのコンテンツを指定するレコードと構造のコレクションである Excel バイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xlsb) |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML マクロ対応スプレッドシート (.xlsm) は、マクロをサポートするスプレッドシート ファイルの一種です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xlsm) |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML スプレッドシート (.xlsx) は、Microsoft Office 2007 のリリースで Microsoft によって導入された Microsoft Excel ドキュメントのよく知られた形式です。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xlsx) |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel テンプレート ファイル (.xlt) は、Microsoft Office スイートの一部として提供されるスプレッドシート アプリケーションである Microsoft Excel で作成されたテンプレート ファイルです。 Microsoft Office 97-2003 では、新しい XLT ファイルの作成と開くことがサポートされていました。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xlt) |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML マクロ有効スプレッドシート テンプレート (.xltm) は、Microsoft Excel によってマクロ有効テンプレート ファイルとして生成されるファイルを表します。 XLTM ファイルの構造は XLTX に似ていますが、XLTX はマクロを使用したテンプレート ファイルの作成をサポートしていません。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xltm) |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML スプレッドシート テンプレート (.xltx) ファイルは、Office OpenXML ファイル形式の仕様に基づいています。 XLTX ファイルで指定されたものと同じ設定を示す XLSX ファイルを生成するために利用できる標準テンプレート ファイルを作成するために使用されます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/spreadsheet/xltx) |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) は、Microsoft によって作成された XML Paper Specifications に基づくページ レイアウト ファイルを表します。 このファイル形式の詳細[ここ](https://docs.fileformat.com/page-description-language/xps) |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | 圧縮ファイル (.zip) |

### 備考

**もっと詳しく知る**

* GroupDocs.Merger でサポートされているファイル形式の詳細: [サポートされているドキュメント形式の完全なリスト](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* コードでサポートされているファイル タイプを取得する方法の詳細: [サポートされているファイル形式をコードで取得する方法](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### 関連項目

* 名前空間 [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* 組み立て [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
