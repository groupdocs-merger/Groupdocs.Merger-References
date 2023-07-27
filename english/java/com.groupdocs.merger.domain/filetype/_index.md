---
title: FileType
second_title: GroupDocs.Merger for Java API Reference
description: Represents file type.
type: docs
weight: 10
url: /java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Represents file type. Provides methods to obtain list of all file types supported by **GroupDocs.Merger**, detect file type by extension etc.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Fields

| Field | Description |
| --- | --- |
| [Unknown](#Unknown) | Represents unknown file type. |
| [ZIP](#ZIP) |  |
| [TAR](#TAR) |  |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) are drawing stencils created with Microsoft Visio 2013 and above. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) represents Microsoft Visio file format introduced from Microsoft Office 2013 onwards. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) are drawing files created with Microsoft Visio application that supports macros. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) are drawing template files created with Microsoft Visio 2013 and above. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) are template files created with Microsoft Visio that support macros. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) are Microsoft Visio Stencil files that support provide support for macros. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) refers to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) is a Microsoft Visio drawing template that is saved to disc in XML file format. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx)is a drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. |
| [EPUB](#EPUB) | Open eBook File (.epub) are an e-book file format that provide a standard digital publication format for publishers and consumers. |
| [BMP](#BMP) | Bitmap Image File (.bmp) represent files that are used to store bitmap digital images. |
| [JPG](#JPG) | JPEG Image (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) is a type of image format that is saved using the method of lossy compression. |
| [PNG](#PNG) | Portable Network Graphic (.png) is a type of raster image file format that use loseless compression. |
| [PS](#PS) | PostScript File (.ps) |
| [TIF](#TIF) | Tagged Image File (.tif) |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics File (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics Compressed File (.svgz) |
| [HTML](#HTML) | Hypertext Markup Language File (.html) is the extension for web pages created for display in browsers. |
| [MHT](#MHT) | MHTML Web Archive (.mht) is a web page archive format that can be created by a number of different applications. |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) is a web page archive format that can be created by a number of different applications. |
| [ONE](#ONE) | OneNote Document (.one) files are created by Microsoft OneNote application. |
| [PDF](#PDF) | Portable Document Format File (.pdf) isa file format that was to introduced as a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. |
| [XPS](#XPS) | XML Paper Specification File (.xps) represents page layout files that are based on XML Paper Specifications created by Microsoft. |
| [TEX](#TEX) | LaTeX Source Document (.tex) is a language that comprises of programming as well as mark-up features, used to typeset documents. |
| [PPT](#PPT) | PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) is a presentation file created with popular Microsoft PowerPoint application. |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) is a file created using Microsoft PowerPoint for Slide Show purpose. |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) is a file created using Microsoft PowerPoint 2007 and above for Slide Show purpose. |
| [ODP](#ODP) | OpenDocument Presentation (.odp) represents presentation file format used by OpenOffice.org in the OASISOpen standard. |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) represents presentation template files created by applications in OASIS OpenDocument standard format. |
| [XLS](#XLS) | Excel Spreadsheet (.xls) is a file that can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is a type of Spreasheet files that support macros. |
| [XLSB](#XLSB) | Excel Binary Spreadsheet (.xlsb) file format specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. |
| [CSV](#CSV) | Comma Separated Values File (.csv) represents plain text files that contain records of data with comma separated values. |
| [TSV](#TSV) | Tab Separated Values File (.tsv) represents data separated with tabs in plain text format. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods) Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/ods |
| [XLTM](#XLTM) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) represents files that are generated by Microsoft Excel as Macro-enabled template files. |
| [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) files are based on the Office OpenXML file format specifications. |
| [XLT](#XLT) | Excel Template File (.xlt) are template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite. |
| [XLAM](#XLAM) | Excel Macro-Enabled Add-In (.xlam) |
| [DOC](#DOC) | Microsoft Word Document (.doc) represent documents generated by Microsoft Word or other word processing documents in binary file format. |
| [DOCX](#DOCX) | Microsoft Word Open XML Document (.docx) is a well-known format for Microsoft Word documents. |
| [DOCM](#DOCM) | Word Open XML Macro-Enabled Document (.docm) files are Microsoft Word 2007 or higher generated documents with the ability to run macros. |
| [DOT](#DOT) | Word Document Template (.dot) files are template files created by Microsoft Word to have pre-formatted settings for generation of further DOC or DOCX files. |
| [DOTX](#DOTX) | Word Open XML Document Template (.dotx) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOCX files. |
| [DOTM](#DOTM) | Word Open XML Macro-Enabled Document Template (.dotm) represents template file created with Microsoft Word 2007 or higher. |
| [RTF](#RTF) | Rich Text Format File (.rtf) introduced and documented by Microsoft, the Rich Text Format (RTF) represents a method of encoding formatted text and graphics for use within applications. |
| [TXT](#TXT) | Plain Text File (.txt) represents a text document that contains plain text in the form of lines. |
| [ERR](#ERR) | Error Log File (.err) is a text file that contains error messages generated by a program. |
| [ODT](#ODT) | OpenDocument Text Document (.odt) files are type of documents created with word processing applications that are based on OpenDocument Text File format. |
| [OTT](#OTT) | OpenDocument Document Template (.ott) represent template documents generated by applications in compliance with the OASIS' OpenDocument standard format. |
## Methods

| Method | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | File type name e.g. |
| [getExtension()](#getExtension--) | Filename suffix (including the period ".") e.g. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Maps file extension to file type. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Retrieves supported file types |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified object. |
| [hashCode()](#hashCode--) | Returns the hash code for the current [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are not the same. |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is archive format. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Represents unknown file type.

### ZIP {#ZIP}
```
public static FileType ZIP
```


### TAR {#TAR}
```
public static FileType TAR
```


### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil File (.vssx) are drawing stencils created with Microsoft Visio 2013 and above. The VSSX file format can be opened with Visio 2013 and above. Visio files are known for representation of a variety of drawing elements such as collection of shapes, connectors, flowcharts, network layout, UML diagrams, Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx) represents Microsoft Visio file format introduced from Microsoft Office 2013 onwards. It was developed to replace the binary file format, .VSD, which is supported by earlier versions of Microsoft Visio. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) are drawing files created with Microsoft Visio application that supports macros. VSDM files are OPC/XML drawings that are similar to VSDX, but also provide the capability to run macros when the file is opened. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) are drawing template files created with Microsoft Visio 2013 and above. These VSTX files provide starting point for creating Visio drawings, saved as .VSDX files, with default layout and settings. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) are template files created with Microsoft Visio that support macros. Unlike VSDX files, files created from VSTM templates can run macros that are developed in Visual Basic for Applications (VBA) code. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) are Microsoft Visio Stencil files that support provide support for macros. A VSSM file when opened allows to run the macros to achieve desired formatting and placement of shapes in a diagram. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) refers to stencils that consist of drawings and shapes that are used for creating diagrams in Microsoft Visio. VSX files are saved in XML file format and was supported till Visio 2013. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) is a Microsoft Visio drawing template that is saved to disc in XML file format. The template is aimed to provide a file with basic settings that can be used to create multiple Visio files of the same settings. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx)is a drawing or chart created in Microsoft Visio, but saved in XML format have .VDX extension. A Visio drawing XML file is created in Visio software, which is developed by Microsoft. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) are an e-book file format that provide a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) represent files that are used to store bitmap digital images. Learn more about this file format  [here][] .


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


JPEG Image (.jpeg) is a type of image format that is saved using the method of lossy compression. The output image, as result of compression, is a trade-off between storage size and image quality. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) is a type of raster image file format that use loseless compression. Learn more about this file format  [here][] .


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

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) is the extension for web pages created for display in browsers. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) is a web page archive format that can be created by a number of different applications. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) is a web page archive format that can be created by a number of different applications. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Document (.one) files are created by Microsoft OneNote application. OneNote lets you gather information using the application as if you are using your draftpad for taking notes. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) isa file format that was to introduced as a standard for representation of documents and other reference material in a format that is independent of application software, hardware as well as Operating System. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) represents page layout files that are based on XML Paper Specifications created by Microsoft. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) is a language that comprises of programming as well as mark-up features, used to typeset documents. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation (.ppt) represents PowerPoint file that consists of a collection of slides for displaying as SlideShow. It specifies the Binary File Format used by Microsoft PowerPoint 97-2003. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation (.pptx) is a presentation file created with popular Microsoft PowerPoint application. Unlike the previous version of presentation file format PPT which was binary, the PPTX format is based on the Microsoft PowerPoint open XML presentation file format. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show (.pps) is a file created using Microsoft PowerPoint for Slide Show purpose. PPS file reading and creation is supported by Microsoft PowerPoint 97-2003. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slide Show (.ppsx) is a file created using Microsoft PowerPoint 2007 and above for Slide Show purpose. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp) represents presentation file format used by OpenOffice.org in the OASISOpen standard. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) represents presentation template files created by applications in OASIS OpenDocument standard format. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) is a file that can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) is a well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is a type of Spreasheet files that support macros. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) file format specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) represents plain text files that contain records of data with comma separated values. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) represents data separated with tabs in plain text format. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods) Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/ods

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) represents files that are generated by Microsoft Excel as Macro-enabled template files. XLTM files are similar to XLTX in structure other than that the later doesn't support creating template files with macros. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) files are based on the Office OpenXML file format specifications. It is used to create a standard template file that can be utilized to generate XLSX files that exhibit the same settings as specified in the XLTX file. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt) are template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite. Microsoft Office 97-2003 supported creating new XLT files as well as opening these. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel Macro-Enabled Add-In (.xlam)

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) represent documents generated by Microsoft Word or other word processing documents in binary file format. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) is a well-known format for Microsoft Word documents. Introduced from 2007 with the release of Microsoft Office 2007, the structure of this new Document format was changed from plain binary to a combination of XML and binary files. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) files are Microsoft Word 2007 or higher generated documents with the ability to run macros. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) files are template files created by Microsoft Word to have pre-formatted settings for generation of further DOC or DOCX files. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) are template files created by Microsoft Word to have pre-formatted settings for generation of further DOCX files. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) represents template file created with Microsoft Word 2007 or higher. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf) introduced and documented by Microsoft, the Rich Text Format (RTF) represents a method of encoding formatted text and graphics for use within applications. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt) represents a text document that contains plain text in the form of lines. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Error Log File (.err) is a text file that contains error messages generated by a program. Learn more about this file format  [here][] .


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) files are type of documents created with word processing applications that are based on OpenDocument Text File format. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) represent template documents generated by applications in compliance with the OASIS' OpenDocument standard format. Learn more about this file format  [here][] .


[here]: https://docs.fileformat.com/word-processing/ott

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


File type name e.g. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Filename suffix (including the period ".") e.g. ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Maps file extension to file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | File extension (including the period "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Retrieves supported file types

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Returns sequence of supported file types
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified [FileType](../../com.groupdocs.merger.domain/filetype) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | The object to compare with the current [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

parameter is [FileType](../../com.groupdocs.merger.domain/filetype) and is the same as current [FileType](../../com.groupdocs.merger.domain/filetype) object; otherwise,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for the current [FileType](../../com.groupdocs.merger.domain/filetype) object.

**Returns:**
int - A hash code for the current [FileType](../../com.groupdocs.merger.domain/filetype) object.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Left [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Right [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are not the same; otherwise,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

if input [FileType](../../com.groupdocs.merger.domain/filetype) is archive format; otherwise,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive image format; otherwise,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
