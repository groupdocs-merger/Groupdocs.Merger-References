---
title: "FileType"
second_title: "GroupDocs.Merger for .NET API 参考"
description: "表示文件类型。提供获取 GroupDocs.Merger 支持的所有文件类型列表、通过扩展名检测文件类型等方法。"
type: docs
weight: 110
url: /zh/net/groupdocs.merger.domain/filetype/
---
## FileType class

表示文件类型。提供获取 **GroupDocs.Merger** 支持的所有文件类型列表、通过扩展名检测文件类型等方法。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | 文件名后缀（包括句点 "."），例如 ".doc"。 |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | 文件类型名称，例如 "Microsoft Word Document"。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | 确定当前 [`FileType`](../filetype) 是否与指定的 [`FileType`](../filetype) 对象相同。 |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | 确定当前 [`FileType`](../filetype) 是否与指定的对象相同。 |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | 返回当前 [`FileType`](../filetype) 对象的哈希码。 |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | 返回表示当前对象的字符串。 |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | 检索受支持的文件类型 |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | 确定输入的 [`FileType`](../filetype) 是否为归档格式。 |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | 确定输入的 [`FileType`](../filetype) 是否为音频格式。 |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | 确定输入的 [`FileType`](../filetype) 是否为图像格式。 |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | 确定输入的 [`FileType`](../filetype) 是否为原始文本格式。 |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | 确定两个 [`FileType`](../filetype) 对象是否相同。 |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | 确定两个 [`FileType`](../filetype) 对象是否不相同。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | 位图图像文件（.bmp）表示用于存储位图数字图像的文件。了解此文件格式的更多信息，请访问[此处](https://docs.fileformat.com/image/bmp)。 |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 压缩文件（.bz2） |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | 逗号分隔值文件（.csv）表示包含逗号分隔数据记录的纯文本文件。了解此文件格式的更多信息，请访问[此处](https://docs.fileformat.com/spreadsheet/csv)。 |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word 文档（.doc）表示由 Microsoft Word 或其他文字处理软件以二进制文件格式生成的文档。了解此文件格式的更多信息，请访问[此处](https://docs.fileformat.com/word-processing/doc)。 |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML 宏启用文档 (.docm) 文件是由 Microsoft Word 2007 或更高版本生成的、能够运行宏的文档。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/docm)。 |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML 文档 (.docx) 是一种广为人知的 Microsoft Word 文档格式。自 2007 年 Microsoft Office 2007 发布起引入，该文档格式的结构由原来的纯二进制改为 XML 与二进制文件的组合。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/docx)。 |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | Word 文档模板 (.dot) 文件是 Microsoft Word 创建的模板文件，用于预先设置格式以生成后续的 DOC 或 DOCX 文件。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/dot)。 |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML 宏启用文档模板 (.dotm) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/dotm)。 |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML 文档模板 (.dotx) 是 Microsoft Word 创建的模板文件，用于预先设置格式以生成后续的 DOCX 文件。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/dotx)。 |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows 增强型图元文件 (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows 压缩增强型图元文件 (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook 文件 (.epub) 是一种电子书文件格式，为出版商和消费者提供标准的数字出版格式。该格式已相当普及，许多电子阅读器和软件应用都支持。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/ebook/epub)。 |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | 错误日志文件 (.err) 是包含程序生成的错误信息的文本文件。了解更多关于此文件格式的信息，请点击[此处](https://fileinfo.com/extension/err)。 |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | 图形互换格式文件 (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip 压缩文件 (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | 超文本标记语言文件 (.html) 是用于在浏览器中显示的网页的扩展名。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/web/html)。 |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG 图像 (.jpeg) 是一种使用有损压缩方法保存的图像格式。压缩后的输出图像在存储大小和图像质量之间进行权衡。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/image/jpeg)。 |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG 图像 (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML 网页存档 (.mht) 是一种可以由多种不同应用程序创建的网页存档格式。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/web/mhtml)。 |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML 文件 (.mhtml) 是一种可以由多种不同应用程序创建的网页存档格式。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/web/mhtml)。 |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | 带有 .mp3 扩展名的文件是用于音频的数字编码文件格式，正式基于 MPEG-1 Audio Layer III 或 MPEG-2 Audio Layer III。它由移动图像专家组 (MPEG) 开发，使用第 3 层音频压缩。MP3 文件格式的压缩率约为 .WAV 或 .AIF 文件的十分之一。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/audio/mp3)。 |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument 演示文稿 (.odp) 表示 OpenOffice.org 在 OASIS Open 标准中使用的演示文稿文件格式。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/presentation/odp)。 |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument 电子表格 (.ods) 了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/spreadsheet/ods)。 |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument 文本文档 (.odt) 文件是基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/odt)。 |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote 文档 (.one) 文件由 Microsoft OneNote 应用程序创建。OneNote 让您像使用草稿本记笔记一样收集信息。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/note-taking/one)。 |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument 演示文稿模板 (.otp) 表示由 OASIS OpenDocument 标准格式的应用程序创建的演示文稿模板文件。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/presentation/otp)。 |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument 文档模板 (.ott) 表示符合 OASIS OpenDocument 标准格式的应用程序生成的模板文档。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/word-processing/ott)。 |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | 便携式文档格式文件 (.pdf) 是一种被引入作为文档及其他参考材料的标准表示形式的文件格式，独立于应用软件、硬件以及操作系统。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/view/pdf)。 |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | 便携式网络图形 (.png) 是一种使用无损压缩的光栅图像文件格式。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/image/png)。 |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML 宏启用演示文稿模板 (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML 演示文稿模板 (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint 幻灯片放映 (.pps) 是使用 Microsoft PowerPoint 创建的用于幻灯片放映的文件。Microsoft PowerPoint 97-2003 支持 PPS 文件的读取和创建。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/presentation/pps)。 |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML 宏启用幻灯片 (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML 幻灯片放映 (.ppsx) 是使用 Microsoft PowerPoint 2007 及以上版本创建的用于幻灯片放映的文件。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/presentation/ppsx)。 |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint 演示文稿 (.ppt) 表示由一系列幻灯片组成的 PowerPoint 文件，用于以幻灯片放映方式显示。它指定了 Microsoft PowerPoint 97-2003 使用的二进制文件格式。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/presentation/ppt)。 |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML 宏启用演示文稿 |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML 演示文稿 (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。不同于之前的二进制 PPT 演示文件格式，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文件格式。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/presentation/pptx)。 |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript 文件 (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive 压缩文件 (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format 文件 (.rtf) 由 Microsoft 引入并文档化，富文本格式（RTF）是一种用于在应用程序中编码格式化文本和图形的方法。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/word-processing/rtf)。 |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip 压缩文件 (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | 可缩放矢量图形文件 (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | 可缩放矢量图形压缩文件 (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | 统一 Unix 文件归档 (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX 源文档 (.tex) 是一种包含编程和标记特性的语言，用于排版文档。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/page-description-language/tex)。 |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | 标签图像文件 (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | 标签图像文件格式 (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tab 分隔值文件 (.tsv) 表示以制表符分隔的纯文本格式数据。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/spreadsheet/tsv)。 |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | 纯文本文件 (.txt) 表示包含以行为单位的纯文本的文档。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/word-processing/txt)。 |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | 表示未知文件类型。 |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio 绘图 XML 文件 (.vdx) 是在 Microsoft Visio 中创建的绘图或图表，但以 XML 格式保存，扩展名为 .VDX。Visio 绘图 XML 文件是在由 Microsoft 开发的 Visio 软件中创建的。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/image/vdx)。 |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | Visio 绘图文件 (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio 宏启用绘图 (.vsdm) 是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。VSDM 文件是类似于 VSDX 的 OPC/XML 绘图，但在打开文件时还能运行宏。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/image/vsdm)。 |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio 绘图 (.vsdx) 表示自 Microsoft Office 2013 起引入的 Microsoft Visio 文件格式。它用于取代早期版本 Microsoft Visio 支持的二进制文件格式 .VSD。了解更多关于此文件格式的信息 [此处](https://docs.fileformat.com/image/vsdx)。 |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | Visio 模板文件(.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio 宏启用模板文件 (.vssm) 是 Microsoft Visio 模板文件，提供对宏的支持。打开 VSSM 文件后，可运行宏以实现对图表中形状的所需格式化和放置。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/image/vssm)。 |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio 模板文件 (.vssx) 是使用 Microsoft Visio 2013 及更高版本创建的绘图模板。VSSX 文件格式可在 Visio 2013 及以上版本中打开。Visio 文件以表示各种绘图元素而闻名，包括形状集合、连接线、流程图、网络布局、UML 图等。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/image/vssx)。 |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Visio 绘图模板 (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio 宏启用绘图模板 (.vstm) 是使用 Microsoft Visio 创建的支持宏的模板文件。与 VSDX 文件不同，基于 VSTM 模板创建的文件可以运行使用 Visual Basic for Applications (VBA) 代码开发的宏。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/image/vstm)。 |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio 绘图模板 (.vstx) 是使用 Microsoft Visio 2013 及以上版本创建的绘图模板文件。这些 VSTX 文件提供了创建 Visio 绘图的起始点，以 .VSDX 文件形式保存，具有默认的布局和设置。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/image/vstx)。 |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio 模板 XML 文件 (.vsx) 指用于在 Microsoft Visio 中创建图表的绘图和形状集合。VSX 文件以 XML 格式保存，支持至 Visio 2013。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/image/vsx)。 |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio 模板 XML 文件 (.vtx) 是以 XML 格式保存到磁盘的 Microsoft Visio 绘图模板。该模板旨在提供一个包含基本设置的文件，可用于创建多个具有相同设置的 Visio 文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/image/vtx)。 |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV，亦称为 WAVE（波形音频文件格式），是 Microsoft 资源交换文件格式（RIFF）规范的一个子集，用于存储数字音频文件。该格式不对比特流进行任何压缩，并以不同的采样率和比特率存储音频录音。它一直是音频 CD 的标准格式之一。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/audio/wav)。 |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel 宏启用加载项 (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel 电子表格 (.xls) 是一种可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建的文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xls)。 |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel 二进制电子表格 (.xlsb) 文件格式指定了 Excel 二进制文件格式，它是一组记录和结构，用于描述 Excel 工作簿的内容。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xlsb)。 |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML 宏启用电子表格 (.xlsm) 是一种支持宏的电子表格文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xlsm)。 |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML 电子表格 (.xlsx) 是一种广为人知的 Microsoft Excel 文档格式，随 Microsoft Office 2007 的发布而推出。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xlsx)。 |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel 模板文件 (.xlt) 是使用 Microsoft Excel（Microsoft Office 套件中的电子表格应用程序）创建的模板文件。Microsoft Office 97-2003 支持创建和打开 XLT 文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xlt)。 |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML 宏启用电子表格模板 (.xltm) 表示由 Microsoft Excel 生成的宏启用模板文件。XLTM 文件在结构上与 XLTX 类似，唯一的区别是后者不支持创建带宏的模板文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xltm)。 |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML 电子表格模板 (.xltx) 文件基于 Office OpenXML 文件格式规范。它用于创建标准模板文件，可用于生成具有 XLTX 文件中指定相同设置的 XLSX 文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/spreadsheet/xltx)。 |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML 纸张规范文件 (.xps) 代表基于 Microsoft 创建的 XML 纸张规范的页面布局文件。了解更多关于此文件格式的信息，请访问[此处](https://docs.fileformat.com/page-description-language/xps)。 |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | 压缩文件 (.zip) |

### 备注

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### 另见

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
