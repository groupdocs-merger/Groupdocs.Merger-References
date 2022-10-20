---
title: FileType
second_title: GroupDocs.Merger for .NET API 参考
description: 表示文件类型提供方法来获取所支持的所有文件类型的列表GroupDocs.Merger 通过扩展名检测文件类型等
type: docs
weight: 100
url: /zh/net/groupdocs.merger.domain/filetype/
---
## FileType class

表示文件类型。提供方法来获取所支持的所有文件类型的列表**GroupDocs.Merger** 通过扩展名检测文件类型等。

```csharp
public sealed class FileType : IEquatable<FileType>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | 文件名后缀（包括句点“.”） 例如“.doc”. |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | 文件类型名称，例如“Microsoft Word 文档”。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | 将文件扩展名映射到文件类型。 |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | 判断当前是否[`FileType`](../filetype)与指定的相同[`FileType`](../filetype)对象. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | 判断当前是否[`FileType`](../filetype)与指定对象相同。 |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | 返回当前的哈希码[`FileType`](../filetype)对象. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | 返回代表当前对象的字符串。 |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | 检索支持的文件类型 |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | 判断是否输入[`FileType`](../filetype)是原始文本格式。 |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | 判断是否输入[`FileType`](../filetype)是原始文本格式。 |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | 判断两个[`FileType`](../filetype)对象是相同的。 |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | 判断两个[`FileType`](../filetype)对象不一样。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | 逗号分隔值文件 (.csv) 表示纯文本文件，其中包含具有逗号分隔值的数据记录。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/csv) |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word 文档 (.doc) 表示由 Microsoft Word 或其他二进制文件格式的文字处理文档生成的文档。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/doc) |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML 启用宏的文档 (.docm) 文件是 Microsoft Word 2007 或更高版本生成的文档，能够运行宏。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/docm) |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML 文档 (.docx) 是一种众所周知的 Microsoft Word 文档格式。从 2007 年随着 Microsoft Office 2007 的发布引入，这种新文档格式的结构从纯二进制更改为 XML 和二进制文件的组合。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/docx) |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word 文档模板 (.dot) 文件是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOC 或 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/dot) |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML 启用宏的文档模板 (.dotm) 表示使用 Microsoft Word 2007 或更高版本创建的模板文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/dotm) |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML 文档模板 (.dotx) 是由 Microsoft Word 创建的模板文件，具有用于生成更多 DOCX 文件的预格式化设置。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/dotx) |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | 打开电子书文件 (.epub) 是一种电子书文件格式，可为出版商和消费者提供标准的数字出版格式。这种格式现在已经非常普遍，许多电子阅读器和软件应用程序都支持它。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/ebook/epub) |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | 错误日志文件 (.err) 是一个文本文件，其中包含程序生成的错误消息。 了解有关此文件格式的更多信息[这里](https://fileinfo.com/extension/err) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | 超文本标记语言文件 (.html) 是为在浏览器中显示而创建的网页的扩展名。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/web/html) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web 存档 (.mht) 是一种网页存档格式，可以由许多不同的应用程序创建。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/web/mhtml) |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML 文件 (.mhtml) 是一种网页存档格式，可由许多不同的应用程序创建。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/web/mhtml) |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument 演示文稿 (.odp) 表示 OpenOffice.org 在 OASISOpen 标准中使用的演示文稿文件格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/presentation/odp) |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument 电子表格 (.ods) 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/ods) |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument 文本文档 (.odt) 文件是使用基于 OpenDocument 文本文件格式的文字处理应用程序创建的文档类型。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/odt) |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote 文档 (.one) 文件由 Microsoft OneNote 应用程序创建。 OneNote 让您可以使用应用程序收集信息，就像使用草稿板记笔记一样。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/note-taking/one) |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument 演示模板 (.otp) 表示由应用程序以 OASIS OpenDocument 标准格式创建的演示模板文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/presentation/otp) |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument 文档模板 (.ott) 表示由应用程序生成的符合 OASIS 的 OpenDocument 标准格式的模板文档。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/ott) |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | 可移植文档格式文件 (.pdf) 是一种文件格式，它被引入作为一种标准，用于以独立于应用软件、硬件和操作系统的格式表示文档和其他参考材料。 了解有关此文件的更多信息格式[这里](https://docs.fileformat.com/view/pdf) |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint 幻灯片放映 (.pps) 是使用 Microsoft PowerPoint 创建的用于幻灯片放映的文件。 Microsoft PowerPoint 97-2003 支持 PPS 文件读取和创建。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/presentation/pps) |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML 幻灯片放映 (.ppsx) 是使用 Microsoft PowerPoint 2007 及更高版本创建的用于幻灯片放映目的的文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/presentation/ppsx) |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint 演示文稿 (.ppt) 表示 PowerPoint 文件，该文件由一组幻灯片组成，用于显示为幻灯片。它指定 Microsoft PowerPoint 97-2003 使用的二进制文件格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/presentation/ppt). |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) 是使用流行的 Microsoft PowerPoint 应用程序创建的演示文件。与以前版本的二进制演示文件格式 PPT 不同，PPTX 格式基于 Microsoft PowerPoint 开放 XML 演示文件格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/presentation/pptx) |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript 文件 (.ps) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | 富文本格式文件 (.rtf) 由 Microsoft 引入和记录，富文本格式 (RTF) 表示一种编码格式化文本和图形以供在应用程序中使用的方法。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/rtf) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX 源文档 (.tex) 是一种包含编程和标记功能的语言，用于排版文档。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/page-description-language/tex) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | 制表符分隔值文件 (.tsv) 表示用纯文本格式的制表符分隔的数据。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/tsv) |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | 纯文本文件 (.txt) 表示包含行形式的纯文本的文本文档。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/word-processing/txt) |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | 表示未知文件类型。 |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio 绘图 XML 文件 (.vdx) 是在 Microsoft Visio 中创建的绘图或图表，但以 XML 格式保存，扩展名为 .VDX。 Visio 绘图 XML 文件是在 Microsoft 开发的 Visio 软件中创建的。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vdx). |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio 启用宏的绘图 (.vsdm) 是使用支持宏的 Microsoft Visio 应用程序创建的绘图文件。 VSDM 文件是类似于 VSDX 的 OPC/XML 工程图，但也提供了在打开文件时运行宏的能力。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vsdm). |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio 绘图 (.vsdx) 表示从 Microsoft Office 2013 开始引入的 Microsoft Visio 文件格式。它的开发是为了替换早期版本的 Microsoft Visio 支持的二进制文件格式 .VSD。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vsdx). |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio 启用宏的模具文件 (.vssm) 是支持宏的 Microsoft Visio 模具文件。 VSSM 文件在打开时允许运行宏以在图表中实现所需的格式和形状放置。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vssm). |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio 模具文件 (.vssx) 是使用 Microsoft Visio 2013 及更高版本创建的绘图模具。 VSSX 文件格式可以用 Visio 2013 及更高版本打开。 Visio 文件以表示各种绘图元素而闻名，例如形状集合、连接器、流程图、网络布局、UML 图、 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vssx). |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio 启用宏的绘图模板 (.vstm) 是使用 Microsoft Visio 创建的支持宏的模板文件。与 VSDX 文件不同，从 VSTM 模板创建的文件可以运行在 Visual Basic for Applications (VBA) 代码中开发的宏。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vstm). |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio 绘图模板 (.vstx) 是使用 Microsoft Visio 2013 及更高版本创建的绘图模板文件。这些 VSTX 文件为创建 Visio 绘图提供了起点，保存为 .VSDX 文件，具有默认布局和设置。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vstx). |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio 模具 XML 文件 (.vsx) 是指由用于在 Microsoft Visio 中创建图表的绘图和形状组成的模具。 VSX 文件以 XML 文件格式保存，并在 Visio 2013 之前受支持。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vsx). |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio 模板 XML 文件 (.vtx) 是一种 Microsoft Visio 绘图模板，以 XML 文件格式保存到光盘。该模板旨在提供具有基本设置的文件，可用于创建具有相同设置的多个 Visio 文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/image/vtx). |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel 启用宏的加载项 (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel 电子表格 (.xls) 是可由 Microsoft Excel 以及其他类似电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建的文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xls) |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel 二进制电子表格 (.xlsb) 文件格式指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xlsb) |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML 启用宏的电子表格 (.xlsm) 是一种支持宏的电子表格文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xlsm) |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML 电子表格 (.xlsx) 是 Microsoft 在 Microsoft Office 2007 版本中引入的一种众所周知的 Microsoft Excel 文档格式。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xlsx) |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel 模板文件 (.xlt) 是使用 Microsoft Excel 创建的模板文件，这是一个电子表格应用程序，是 Microsoft Office 套件的一部分。 Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xlt) |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML 启用宏的电子表格模板 (.xltm) 将 Microsoft Excel 生成的文件表示为启用宏的模板文件。 XLTM 文件在结构上与 XLTX 相似，只是后者不支持使用宏创建模板文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xltm) |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML 电子表格模板 (.xltx) 文件基于 Office OpenXML 文件格式规范。它用于创建一个标准模板文件，该文件可用于生成 XLSX 文件，这些文件具有与 XLTX 文件中指定的相同的设置。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xltx) |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML 纸张规范文件 (.xps) 表示基于 Microsoft 创建的 XML 纸张规范的页面布局文件。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/page-description-language/xps) |

### 评论

**学到更多**

* 了解有关 GroupDocs.Merger 支持的文件格式的更多信息： [支持的文档格式的完整列表](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* 了解有关在代码中获取支持的文件类型的更多信息： [如何在代码中获取支持的文件格式](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### 也可以看看

* 命名空间 [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* 部件 [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
