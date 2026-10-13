---
title: "FileType"
second_title: "GroupDocs.Merger 适用于 Java 的 API 参考"
description: "表示文件类型。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

表示文件类型。提供获取 **GroupDocs.Merger** 支持的所有文件类型列表、通过扩展名检测文件类型等方法。

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## 字段

| 字段 | 描述 |
| --- | --- |
| [Unknown](#Unknown) | 表示未知文件类型。 |
| [ZIP](#ZIP) | 压缩文件 (.zip) |
| [SevenZ](#SevenZ) | 7-Zip 压缩文件 (.7z) |
| [TAR](#TAR) | 统一 Unix 文件归档 (.tar) |
| [RAR](#RAR) | Roshal 压缩归档文件 (.rar) |
| [VSSX](#VSSX) | Visio 模板文件 (.vssx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。 |
| [VSDX](#VSDX) | Visio 绘图文件 (.vsdx) 表示自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。 |
| [VSDM](#VSDM) | Visio 启用宏的绘图文件 (.vsdm) 是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。 |
| [VSTX](#VSTX) | Visio 绘图模板 (.vstx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。 |
| [VSTM](#VSTM) | Visio 启用宏的绘图模板 (.vstm) 是使用支持宏的 Microsoft Visio 创建的模板文件。 |
| [VSSM](#VSSM) | Visio 启用宏的模板文件 (.vssm) 是支持宏的 Microsoft Visio 模板文件。 |
| [VSX](#VSX) | Visio 模板 XML 文件 (.vsx) 指由用于在 Microsoft Visio 中创建图表的绘图和形状组成的模板。 |
| [VTX](#VTX) | Visio 模板 XML 文件 (.vtx) 是以 XML 文件格式保存到磁盘的 Microsoft Visio 绘图模板。 |
| [VDX](#VDX) | Visio 绘图 XML 文件 (.vdx) 是在 Microsoft Visio 中创建的绘图或图表，但以 XML 格式保存，使用 .VDX 扩展名。 |
| [EPUB](#EPUB) | Open eBook File (.epub) 是一种电子书文件格式，提供面向出版商和消费者的标准数字出版格式。 |
| [BMP](#BMP) | Bitmap Image File (.bmp) 表示用于存储位图数字图像的文件。 |
| [JPG](#JPG) | JPEG Image (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) 是一种使用有损压缩方式保存的图像格式。 |
| [PNG](#PNG) | Portable Network Graphic (.png) 是一种使用无损压缩的光栅图像文件格式。 |
| [PS](#PS) | PostScript File (.ps) |
| [TIF](#TIF) | Tagged Image File (.tif) |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics File (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics Compressed File (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Hypertext Markup Language File (.html) 是用于在浏览器中显示的网页的扩展名。 |
| [MHT](#MHT) | MHTML Web Archive (.mht) 是一种可以由多种不同应用程序创建的网页存档格式。 |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) 是一种可以由多种不同应用程序创建的网页存档格式。 |
| [ONE](#ONE) | OneNote Document (.one) 文件由 Microsoft OneNote 应用程序创建。 |
| [PDF](#PDF) | Portable Document Format File (.pdf) 是一种文件格式，作为独立于应用软件、硬件以及操作系统的文档和其他参考材料的标准表示形式而被引入。 |
| [XPS](#XPS) | XML Paper Specification File (.xps) 表示基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。 |
| [TEX](#TEX) | LaTeX Source Document (.tex) 是一种包含编程和标记功能的语言，用于排版文档。 |
| [PPT](#PPT) | PowerPoint Presentation (.ppt) 表示包含一系列幻灯片用于幻灯片放映的 PowerPoint 文件。 |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。 |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) 是使用 Microsoft PowerPoint 为幻灯片放映目的创建的文件。 |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) 是使用 Microsoft PowerPoint 2007 及以上版本为幻灯片放映目的创建的文件。 |
| [ODP](#ODP) | OpenDocument Presentation (.odp) 表示在 OASIS Open 标准中由 OpenOffice.org 使用的演示文件格式。 |
| [OTP](#OTP) | OpenDocument 演示文稿模板（.otp）表示由符合 OASIS OpenDocument 标准格式的应用程序创建的演示文稿模板文件。 |
| [PPTM](#PPTM) | PowerPoint Open XML 启用宏的演示文稿 |
| [XLS](#XLS) | Excel 电子表格（.xls）是一种文件，可由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。 |
| [XLSX](#XLSX) | Microsoft Excel Open XML 电子表格（.xlsx）是一种广为人知的 Microsoft Excel 文档格式，随 Microsoft Office 2007 发布而由 Microsoft 推出。 |
| [XLSM](#XLSM) | Excel Open XML 启用宏的电子表格（.xlsm）是一种支持宏的电子表格文件类型。 |
| [XLSB](#XLSB) | Excel 二进制电子表格（.xlsb）文件格式指定了 Excel 二进制文件格式，它是一组记录和结构的集合，用于定义 Excel 工作簿的内容。 |
| [CSV](#CSV) | 逗号分隔值文件（.csv）表示包含以逗号分隔的数据记录的纯文本文件。 |
| [TSV](#TSV) | 制表符分隔值文件（.tsv）表示以制表符分隔的数据，采用纯文本格式。 |
| [ODS](#ODS) | OpenDocument 电子表格（.ods）。 |
| [XLTM](#XLTM) | Excel Open XML 启用宏的电子表格模板（.xltm）表示由 Microsoft Excel 生成的宏启用模板文件。 |
| [XLTX](#XLTX) | Excel Open XML 电子表格模板（.xltx）文件基于 Office OpenXML 文件格式规范。 |
| [XLT](#XLT) | Excel 模板文件（.xlt）是使用 Microsoft Excel 创建的模板文件，Excel 是 Microsoft Office 套件中的电子表格应用程序。 |
| [XLAM](#XLAM) | Excel 启用宏的加载项（.xlam）。 |
| [DOC](#DOC) | Microsoft Word 文档（.doc）表示由 Microsoft Word 或其他文字处理程序以二进制文件格式生成的文档。 |
| [DOCX](#DOCX) | Microsoft Word Open XML 文档（.docx）是一种广为人知的 Microsoft Word 文档格式。 |
| [DOCM](#DOCM) | Word Open XML 启用宏的文档（.docm）文件是由 Microsoft Word 2007 及更高版本生成的、具备运行宏功能的文档。 |
| [DOT](#DOT) | Word 文档模板（.dot）文件是由 Microsoft Word 创建的模板文件，具有预设格式设置，以便生成后续的 DOC 或 DOCX 文件。 |
| [DOTX](#DOTX) | Word Open XML 文档模板（.dotx）是由 Microsoft Word 创建的模板文件，具有预设格式设置，以便生成后续的 DOCX 文件。 |
| [DOTM](#DOTM) | Word Open XML 启用宏的文档模板（.dotm）表示由 Microsoft Word 2007 及更高版本创建的模板文件。 |
| [RTF](#RTF) | Rich Text Format 文件（.rtf）由 Microsoft 引入并记录，富文本格式（RTF）是一种用于在应用程序中编码格式化文本和图形的方法。 |
| [TXT](#TXT) | 纯文本文件（.txt）表示以行形式包含纯文本的文本文档。 |
| [ERR](#ERR) | 错误日志文件（.err）是一种包含程序生成的错误信息的文本文件。 |
| [ODT](#ODT) | OpenDocument 文本文档（.odt）文件是一类基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档。 |
| [OTT](#OTT) | OpenDocument 文档模板（.ott）表示符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。 |
| [WAV](#WAV) | WAV，亦称为 WAVE（波形音频文件格式），是 Microsoft 的资源互换文件格式（RIFF）规范的一个子集，用于存储数字音频文件。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | 文件类型名称，例如。 |
| [getExtension()](#getExtension--) | 文件名后缀（包括句点 "."），例如。 |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | 将文件扩展名映射到文件类型。 |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | 检索受支持的文件类型 |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | 确定当前的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否与指定的 [FileType](../../com.groupdocs.merger.domain/filetype) 对象相同。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定当前的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否与指定的对象相同。 |
| [hashCode()](#hashCode--) | 返回当前 [FileType](../../com.groupdocs.merger.domain/filetype) 对象的哈希码。 |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 确定两个 [FileType](../../com.groupdocs.merger.domain/filetype) 对象是否相同。 |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 确定两个 [FileType](../../com.groupdocs.merger.domain/filetype) 对象是否不相同。 |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | 确定输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否为原始文本格式。 |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | 确定输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否为归档格式。 |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | 确定输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否为原始文本格式。 |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | 确定输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否为音频格式。 |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


表示未知文件类型。

### ZIP {#ZIP}
```
public static FileType ZIP
```


压缩文件 (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


7-Zip 压缩文件 (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


统一 Unix 文件归档 (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal 压缩归档文件 (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio 模板文件（.vssx）是使用 Microsoft Visio 2013 及以上版本创建的绘图模板。VSSX 文件格式可在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接线、流程图、网络布局、UML 图等。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio 绘图文件（.vsdx）代表自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它用于取代早期版本的二进制文件格式 .VSD。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio 启用宏的绘图文件（.vsdm）是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但还具备在打开文件时运行宏的能力。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio 绘图模板（.vstx）是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件提供了创建 Visio 绘图的起始点，保存为 .VSDX 文件，并带有默认布局和设置。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio 启用宏的绘图模板（.vstm）是使用支持宏的 Microsoft Visio 创建的模板文件。与 VSDX 文件不同，基于 VSTM 模板创建的文件可以运行使用 Visual Basic for Applications（VBA）代码开发的宏。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio 启用宏的模板文件（.vssm）是支持宏的 Microsoft Visio 模板文件。打开 VSSM 文件后，可运行宏以实现图表中形状的所需格式化和放置。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio 模板 XML 文件（.vsx）指用于在 Microsoft Visio 中创建图表的绘图和形状集合。VSX 文件以 XML 格式保存，支持至 Visio 2013。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio 模板 XML 文件（.vtx）是以 XML 格式保存到磁盘的 Microsoft Visio 绘图模板。该模板旨在提供包含基本设置的文件，可用于创建多个具有相同设置的 Visio 文件。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio 绘图 XML 文件（.vdx）是使用 Microsoft Visio 创建的绘图或图表，但以 .VDX 扩展名的 XML 格式保存。Visio 绘图 XML 文件是在 Microsoft 开发的 Visio 软件中创建的。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook 文件（.epub）是一种为出版商和消费者提供标准数字出版格式的电子书文件格式。该格式现已非常普及，受到众多电子阅读器和软件应用的支持。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


位图图像文件（.bmp）用于存储位图数字图像。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Image (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG 图像（.jpeg）是一种使用有损压缩方法保存的图像格式。压缩后得到的输出图像在存储大小和图像质量之间进行权衡。了解此文件格式的更多信息，请访问 [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) 是一种使用无损压缩的栅格图像文件格式。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript File (.ps)

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


Graphical Interchange Format File (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Scalable Vector Graphics File (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Scalable Vector Graphics Compressed File (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Windows Enhanced Metafile (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Compressed Enhanced Metafile (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) 是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) 是一种可以由多种不同应用程序创建的网页存档格式。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) 是一种可以由多种不同应用程序创建的网页存档格式。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Document (.one) 文件由 Microsoft OneNote 应用程序创建。OneNote 让您可以使用该应用程序收集信息，就像使用草稿本记笔记一样。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) 是一种被引入作为文档及其他参考材料的标准表示形式的文件格式，该格式独立于应用软件、硬件以及操作系统。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) 代表基于 Microsoft 创建的 XML Paper Specification 的页面布局文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) 是一种包含编程和标记功能的语言，用于排版文档。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation (.ppt) 代表由一系列幻灯片组成的 PowerPoint 文件，用于以幻灯片放映方式显示。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。不同于之前的二进制 PPT 演示文件格式，PPTX 格式基于 Microsoft PowerPoint 开放的 XML 演示文件格式。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show (.pps) 是使用 Microsoft PowerPoint 创建用于幻灯片放映的文件。Microsoft PowerPoint 97-2003 支持 PPS 文件的读取和创建。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slide Show (.ppsx) 是使用 Microsoft PowerPoint 2007 及以上版本创建用于幻灯片放映的文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp) 代表 OpenOffice.org 在 OASIS Open 标准中使用的演示文件格式。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) 代表使用 OASIS OpenDocument 标准格式的应用程序创建的演示模板文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/presentation/otp

### PPTM {#PPTM}
```
public static FileType PPTM
```


PowerPoint Open XML 启用宏的演示文稿

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) 是一种可以由 Microsoft Excel 以及其他类似电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建的文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) 是一种为 Microsoft Excel 文档而知名的格式，由 Microsoft 在 Microsoft Office 2007 发布时引入。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) 是一种支持宏的电子表格文件类型。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) 文件格式指定了 Excel 二进制文件格式，它是一组记录和结构，用于定义 Excel 工作簿的内容。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) 代表包含以逗号分隔值的数据记录的纯文本文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) 代表以制表符分隔的纯文本格式数据。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument 电子表格（.ods）。

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) 代表由 Microsoft Excel 生成的宏启用模板文件。XLTM 文件在结构上类似于 XLTX，唯一的区别是后者不支持创建带宏的模板文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) 文件基于 Office OpenXML 文件格式规范。它用于创建标准模板文件，可用于生成具有与 XLTX 文件中指定的相同设置的 XLSX 文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt) 是使用 Microsoft Excel（Microsoft Office 套件中的电子表格应用程序）创建的模板文件。Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel 启用宏的加载项（.xlam）。

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) 代表由 Microsoft Word 或其他文字处理程序以二进制文件格式生成的文档。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) 是一种为 Microsoft Word 文档而知名的格式。自 2007 年 Microsoft Office 2007 发布起，引入了该格式，其结构从纯二进制更改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请点击[here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) 文件是由 Microsoft Word 2007 或更高版本生成的、能够运行宏的文档。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) 文件是由 Microsoft Word 创建的模板文件，具有预设的格式设置，用于生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) 是由 Microsoft Word 创建的模板文件，具有预设的格式设置，用于生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf) 由 Microsoft 引入并记录，富文本格式（RTF）是一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt) 表示一种以行形式包含纯文本的文档。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Error Log File (.err) 是一种包含程序生成的错误信息的文本文件。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) 文件是一类基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) 表示符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV，亦称为 WAVE（波形音频文件格式），是 Microsoft’s 资源互换文件格式（RIFF）规范的一个子集，用于存储数字音频文件。该格式不对比特流进行任何压缩，并以不同的采样率和比特率存储音频录音。它一直是音频 CD 的标准格式之一。了解更多关于此文件格式的信息，请访问[here][].


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


文件类型名称，例如 "Microsoft Word Document"。

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


文件名后缀（包括句点 "."），例如 ".doc"。

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


将文件扩展名映射到文件类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 扩展名 | java.lang.String | 文件扩展名（包括句点 "."）。 |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


检索受支持的文件类型

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - 返回受支持文件类型的序列
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


确定当前的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否与指定的 [FileType](../../com.groupdocs.merger.domain/filetype) 对象相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | 用于与当前 [FileType](../../com.groupdocs.merger.domain/filetype) 对象比较的对象。 |

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

参数是 [FileType](../../com.groupdocs.merger.domain/filetype) 并且与当前的 [FileType](../../com.groupdocs.merger.domain/filetype) 对象相同；否则，

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回当前 [FileType](../../com.groupdocs.merger.domain/filetype) 对象的哈希码。

**Returns:**
int - 当前 [FileType](../../com.groupdocs.merger.domain/filetype) 对象的哈希码。
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


确定两个 [FileType](../../com.groupdocs.merger.domain/filetype) 对象是否相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | 左侧 [FileType](../../com.groupdocs.merger.domain/filetype) 对象。 |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | 右侧 [FileType](../../com.groupdocs.merger.domain/filetype) 对象。 |

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

如果两个 [FileType](../../com.groupdocs.merger.domain/filetype) 对象不相同；否则，

```
false
```
### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


确定输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否为原始文本格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 该 [FileType](../../com.groupdocs.merger.domain/filetype) 对象。 |

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

如果输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 为归档格式；否则，

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


确定输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 是否为原始文本格式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 该 [FileType](../../com.groupdocs.merger.domain/filetype) 对象。 |

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

如果输入的 [FileType](../../com.groupdocs.merger.domain/filetype) 为音频格式；否则，

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
