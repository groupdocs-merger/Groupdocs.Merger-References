---
title: "FileType"
second_title: "Referencia de API de GroupDocs.Merger para Java"
description: "Representa el tipo de archivo."
type: docs
weight: 10
url: /es/java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Representa el tipo de archivo. Proporciona métodos para obtener la lista de todos los tipos de archivo compatibles con **GroupDocs.Merger**, detectar el tipo de archivo por extensión, etc.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Campos

| Campo | Descripción |
| --- | --- |
| [Unknown](#Unknown) | Representa un tipo de archivo desconocido. |
| [ZIP](#ZIP) | Archivo comprimido (.zip) |
| [SevenZ](#SevenZ) | Archivo comprimido 7-Zip (.7z) |
| [TAR](#TAR) | Archivo consolidado Unix (.tar) |
| [RAR](#RAR) | Archivo comprimido Roshal ARchive (.rar) |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) representa el formato de archivo de Microsoft Visio introducido a partir de Microsoft Office 2013. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) son archivos de plantilla creados con Microsoft Visio que admiten macros. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) son archivos de plantilla Microsoft Visio que proporcionan soporte para macros. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) se refiere a plantillas que consisten en dibujos y formas que se utilizan para crear diagramas en Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) es una plantilla de dibujo de Microsoft Visio que se guarda en disco en formato de archivo XML. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) es un dibujo o gráfico creado en Microsoft Visio, pero guardado en formato XML con extensión .VDX. |
| [EPUB](#EPUB) | Open eBook File (.epub) es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. |
| [BMP](#BMP) | Bitmap Image File (.bmp) representa archivos que se utilizan para almacenar imágenes digitales bitmap. |
| [JPG](#JPG) | JPEG Image (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. |
| [PNG](#PNG) | Portable Network Graphic (.png) es un tipo de formato de archivo de imagen raster que utiliza compresión sin pérdida. |
| [PS](#PS) | PostScript File (.ps) |
| [TIF](#TIF) | Tagged Image File (.tif) |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics File (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics Compressed File (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Hypertext Markup Language File (.html) es la extensión para páginas web creadas para mostrarse en navegadores. |
| [MHT](#MHT) | MHTML Web Archive (.mht) es un formato de archivo de página web que puede ser creado por varias aplicaciones diferentes. |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) es un formato de archivo de página web que puede ser creado por varias aplicaciones diferentes. |
| [ONE](#ONE) | OneNote Document (.one) son archivos creados por la aplicación Microsoft OneNote. |
| [PDF](#PDF) | Portable Document Format File (.pdf) es un formato de archivo que se introdujo como estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. |
| [XPS](#XPS) | XML Paper Specification File (.xps) representa archivos de diseño de página basados en XML Paper Specifications creadas por Microsoft. |
| [TEX](#TEX) | LaTeX Source Document (.tex) es un lenguaje que comprende características de programación y de marcado, utilizado para componer documentos. |
| [PPT](#PPT) | PowerPoint Presentation (.ppt) representa un archivo de PowerPoint que consiste en una colección de diapositivas para mostrarse como presentación. |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) es un archivo de presentación creado con la popular aplicación Microsoft PowerPoint. |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) es un archivo creado con Microsoft PowerPoint para propósitos de presentación. |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) es un archivo creado con Microsoft PowerPoint 2007 o superior para propósitos de presentación. |
| [ODP](#ODP) | OpenDocument Presentation (.odp) representa el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. |
| [OTP](#OTP) | La plantilla de presentación OpenDocument (.otp) representa archivos de plantilla de presentación creados por aplicaciones en el formato estándar OpenDocument de OASIS. |
| [PPTM](#PPTM) | Presentación de PowerPoint Open XML con macros habilitadas |
| [XLS](#XLS) | La hoja de cálculo Excel (.xls) es un archivo que puede ser creado por Microsoft Excel así como por otros programas de hoja de cálculo similares, como OpenOffice Calc o Apple Numbers. |
| [XLSX](#XLSX) | El formato de hoja de cálculo Open XML de Microsoft Excel (.xlsx) es un formato bien conocido para documentos de Microsoft Excel que fue introducido por Microsoft con el lanzamiento de Microsoft Office 2007. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) es un tipo de archivo de hoja de cálculo que admite macros. |
| [XLSB](#XLSB) | El formato de archivo Excel Binary Spreadsheet (.xlsb) especifica el Excel Binary File Format, que es una colección de registros y estructuras que definen el contenido del libro de Excel. |
| [CSV](#CSV) | El archivo de valores separados por comas (.csv) representa archivos de texto plano que contienen registros de datos con valores separados por comas. |
| [TSV](#TSV) | El archivo de valores separados por tabulaciones (.tsv) representa datos separados por tabuladores en formato de texto plano. |
| [ODS](#ODS) | Hoja de cálculo OpenDocument (.ods). |
| [XLTM](#XLTM) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) representa archivos que son generados por Microsoft Excel como plantillas con macros habilitadas. |
| [XLTX](#XLTX) | Los archivos Excel Open XML Spreadsheet Template (.xltx) se basan en las especificaciones del formato de archivo Office OpenXML. |
| [XLT](#XLT) | El archivo de plantilla de Excel (.xlt) son archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo incluida en la suite Microsoft Office. |
| [XLAM](#XLAM) | Complemento de Excel con macros habilitadas (.xlam). |
| [DOC](#DOC) | El documento Microsoft Word (.doc) representa documentos generados por Microsoft Word u otros procesadores de texto en formato de archivo binario. |
| [DOCX](#DOCX) | El documento Microsoft Word Open XML (.docx) es un formato bien conocido para documentos de Microsoft Word. |
| [DOCM](#DOCM) | Los archivos Word Open XML Macro-Enabled Document (.docm) son documentos generados por Microsoft Word 2007 o versiones posteriores con la capacidad de ejecutar macros. |
| [DOT](#DOT) | Los archivos Word Document Template (.dot) son plantillas creadas por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOC o DOCX. |
| [DOTX](#DOTX) | Los archivos Word Open XML Document Template (.dotx) son plantillas creadas por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOCX. |
| [DOTM](#DOTM) | Word Open XML Macro-Enabled Document Template (.dotm) representa una plantilla creada con Microsoft Word 2007 o versiones posteriores. |
| [RTF](#RTF) | El archivo Rich Text Format (.rtf), introducido y documentado por Microsoft, representa un método de codificación de texto formateado y gráficos para su uso dentro de aplicaciones. |
| [TXT](#TXT) | El archivo de texto plano (.txt) representa un documento de texto que contiene texto sin formato en forma de líneas. |
| [ERR](#ERR) | El archivo de registro de errores (.err) es un archivo de texto que contiene mensajes de error generados por un programa. |
| [ODT](#ODT) | Los archivos OpenDocument Text Document (.odt) son un tipo de documentos creados con aplicaciones de procesamiento de texto basadas en el formato OpenDocument Text. |
| [OTT](#OTT) | OpenDocument Document Template (.ott) representa documentos plantilla generados por aplicaciones que cumplen con el formato estándar OpenDocument de OASIS. |
| [WAV](#WAV) | WAV, conocido por WAVE (Waveform Audio File Format), es un subconjunto de la especificación Resource Interchange File Format (RIFF) de Microsoft para almacenar archivos de audio digital. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Nombre del tipo de archivo, p. ej. |
| [getExtension()](#getExtension--) | Sufijo del nombre de archivo (incluyendo el punto ".") p. ej. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Asocia la extensión de archivo con el tipo de archivo. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Obtiene los tipos de archivo compatibles |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) actual es el mismo que el objeto [FileType](../../com.groupdocs.merger.domain/filetype) especificado. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) actual es el mismo que el objeto especificado. |
| [hashCode()](#hashCode--) | Devuelve el código hash del objeto [FileType](../../com.groupdocs.merger.domain/filetype) actual. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Determina si dos objetos [FileType](../../com.groupdocs.merger.domain/filetype) son iguales. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Determina si dos objetos [FileType](../../com.groupdocs.merger.domain/filetype) no son iguales. |
| [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) de entrada es un formato de texto primitivo. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) de entrada es un formato de archivo comprimido. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) de entrada es un formato de texto primitivo. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) de entrada es un formato de audio. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Representa un tipo de archivo desconocido.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Archivo comprimido (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


Archivo comprimido 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Archivo consolidado Unix (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Archivo comprimido Roshal ARchive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


El archivo de plantilla de Visio (.vssx) son plantillas de dibujo creadas con Microsoft Visio 2013 y versiones posteriores. El formato de archivo VSSX se puede abrir con Visio 2013 y versiones posteriores. Los archivos de Visio son conocidos por representar una variedad de elementos de dibujo, como colecciones de formas, conectores, diagramas de flujo, diseños de red, diagramas UML. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


El dibujo de Visio (.vsdx) representa el formato de archivo de Microsoft Visio introducido a partir de Microsoft Office 2013. Fue desarrollado para reemplazar el formato de archivo binario, .VSD, que es compatible con versiones anteriores de Microsoft Visio. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


El dibujo con macros de Visio (.vsdm) son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. Los archivos VSDM son dibujos OPC/XML similares a VSDX, pero también ofrecen la capacidad de ejecutar macros cuando se abre el archivo. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


La plantilla de dibujo de Visio (.vstx) son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y versiones posteriores. Estos archivos VSTX proporcionan un punto de partida para crear dibujos de Visio, guardados como archivos .VSDX, con diseño y configuraciones predeterminados. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


La plantilla de dibujo con macros de Visio (.vstm) son archivos de plantilla creados con Microsoft Visio que admiten macros. A diferencia de los archivos VSDX, los archivos creados a partir de plantillas VSTM pueden ejecutar macros desarrolladas en código Visual Basic for Applications (VBA). Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


El archivo de plantilla con macros de Visio (.vssm) son archivos de plantilla de Microsoft Visio que admiten macros. Un archivo VSSM, al abrirse, permite ejecutar las macros para lograr el formato y la ubicación deseados de las formas en un diagrama. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


El archivo de plantilla XML de Visio (.vsx) se refiere a plantillas que consisten en dibujos y formas utilizadas para crear diagramas en Microsoft Visio. Los archivos VSX se guardan en formato XML y fueron compatibles hasta Visio 2013. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


El archivo de plantilla XML de Visio (.vtx) es una plantilla de dibujo de Microsoft Visio que se guarda en disco en formato XML. La plantilla está diseñada para proporcionar un archivo con configuraciones básicas que pueden usarse para crear múltiples archivos de Visio con los mismos ajustes. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


El archivo XML de dibujo de Visio (.vdx) es un dibujo o gráfico creado en Microsoft Visio, pero guardado en formato XML con extensión .VDX. Un archivo XML de dibujo de Visio se crea en el software Visio, desarrollado por Microsoft. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


El archivo Open eBook (.epub) es un formato de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. El formato se ha vuelto tan común que es compatible con muchos lectores electrónicos y aplicaciones de software. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


El archivo de imagen Bitmap (.bmp) representa archivos que se utilizan para almacenar imágenes digitales bitmap. Obtenga más información sobre este formato de archivo [here][].


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


La imagen JPEG (.jpeg) es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen resultante, como resultado de la compresión, es un compromiso entre el tamaño de almacenamiento y la calidad de la imagen. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) es un tipo de formato de archivo de imagen raster que utiliza compresión sin pérdida. Obtenga más información sobre este formato de archivo [here][].


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


El archivo Hypertext Markup Language (.html) es la extensión para páginas web creadas para mostrarse en navegadores. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) es un formato de archivo de archivo web que puede ser creado por varias aplicaciones diferentes. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) es un formato de archivo de archivo web que puede ser creado por varias aplicaciones diferentes. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


Los archivos OneNote Document (.one) son creados por la aplicación Microsoft OneNote. OneNote le permite recopilar información usando la aplicación como si estuviera usando su bloc de notas para tomar notas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) es un formato de archivo que se introdujo como estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) representa archivos de diseño de página basados en las especificaciones XML Paper creadas por Microsoft. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) es un lenguaje que comprende características de programación y de marcado, utilizado para componer documentos. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation (.ppt) representa un archivo de PowerPoint que consiste en una colección de diapositivas para mostrarse como presentación. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation (.pptx) es un archivo de presentación creado con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de archivo de presentación Open XML de Microsoft PowerPoint. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show (.pps) es un archivo creado con Microsoft PowerPoint para propósitos de presentación. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slide Show (.ppsx) es un archivo creado con Microsoft PowerPoint 2007 y versiones posteriores para propósitos de presentación. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp) representa el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASIS Open. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) representa archivos de plantilla de presentación creados por aplicaciones en el formato estándar OASIS OpenDocument. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/presentation/otp

### PPTM {#PPTM}
```
public static FileType PPTM
```


Presentación de PowerPoint Open XML con macros habilitadas

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) es un archivo que puede ser creado por Microsoft Excel así como por otros programas de hoja de cálculo similares, como OpenOffice Calc o Apple Numbers. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) es un formato bien conocido para documentos de Microsoft Excel que fue introducido por Microsoft con el lanzamiento de Microsoft Office 2007. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) es un tipo de archivo de hoja de cálculo que admite macros. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


El formato de archivo Excel Binary Spreadsheet (.xlsb) especifica el Excel Binary File Format, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


El archivo de valores separados por comas (.csv) representa archivos de texto plano que contienen registros de datos con valores separados por comas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


El archivo de valores separados por tabulaciones (.tsv) representa datos separados por tabuladores en formato de texto plano. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Hoja de cálculo OpenDocument (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


La plantilla de hoja de cálculo con macros de Excel Open XML (.xltm) representa archivos que son generados por Microsoft Excel como archivos de plantilla con macros habilitadas. Los archivos XLTM son similares a los XLTX en estructura, excepto que estos últimos no admiten la creación de archivos de plantilla con macros. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Los archivos de plantilla de hoja de cálculo Excel Open XML (.xltx) se basan en las especificaciones del formato de archivo Office OpenXML. Se utilizan para crear un archivo de plantilla estándar que puede emplearse para generar archivos XLSX que presenten la misma configuración que la especificada en el archivo XLTX. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Los archivos de plantilla de Excel (.xlt) son archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo incluida en la suite Microsoft Office. Microsoft Office 97-2003 admitía la creación de nuevos archivos XLT así como su apertura. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Complemento de Excel con macros habilitadas (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


El documento de Microsoft Word (.doc) representa documentos generados por Microsoft Word u otros procesadores de texto en formato de archivo binario. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


El documento Open XML de Microsoft Word (.docx) es un formato bien conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento cambió de binario plano a una combinación de archivos XML y binarios. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Los archivos de documento Open XML con macros habilitadas de Word (.docm) son documentos generados por Microsoft Word 2007 o versiones posteriores con la capacidad de ejecutar macros. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Los archivos de plantilla de documento de Word (.dot) son archivos de plantilla creados por Microsoft Word para tener configuraciones predefinidas para la generación de futuros archivos DOC o DOCX. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Los archivos de plantilla de documento Open XML de Word (.dotx) son archivos de plantilla creados por Microsoft Word para tener configuraciones predefinidas para la generación de futuros archivos DOCX. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


La plantilla de documento Open XML con macros habilitadas de Word (.dotm) representa un archivo de plantilla creado con Microsoft Word 2007 o versiones posteriores. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


El archivo Rich Text Format (.rtf), introducido y documentado por Microsoft, representa un método de codificación de texto con formato y gráficos para su uso en aplicaciones. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


El archivo de texto plano (.txt) representa un documento de texto que contiene texto sin formato en forma de líneas. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


El archivo de registro de errores (.err) es un archivo de texto que contiene mensajes de error generados por un programa. Obtenga más información sobre este formato de archivo [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


Los archivos de documento de texto OpenDocument (.odt) son un tipo de documentos creados con aplicaciones de procesamiento de texto basadas en el formato de archivo OpenDocument Text. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


La plantilla de documento OpenDocument (.ott) representa documentos plantilla generados por aplicaciones que cumplen con el formato estándar OpenDocument de OASIS. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, conocido como WAVE (Waveform Audio File Format), es un subconjunto de la especificación Resource Interchange File Format (RIFF) de Microsoft para almacenar archivos de audio digital. El formato no aplica ninguna compresión al flujo de bits y almacena las grabaciones de audio con diferentes tasas de muestreo y tasas de bits. Ha sido y sigue siendo uno de los formatos estándar para CDs de audio. Obtenga más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Nombre del tipo de archivo, p. ej., "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Sufijo del nombre de archivo (incluyendo el punto ".") p. ej., ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Asocia la extensión de archivo con el tipo de archivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| extensión | java.lang.String | Extensión de archivo (incluyendo el punto "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Obtiene los tipos de archivo compatibles

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Devuelve la secuencia de tipos de archivo compatibles
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) actual es el mismo que el objeto [FileType](../../com.groupdocs.merger.domain/filetype) especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | El objeto para comparar con el actual objeto [FileType](../../com.groupdocs.merger.domain/filetype). |

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

si

```
obj
```

el parámetro es [FileType](../../com.groupdocs.merger.domain/filetype) y es el mismo que el actual objeto [FileType](../../com.groupdocs.merger.domain/filetype); de lo contrario,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash del objeto [FileType](../../com.groupdocs.merger.domain/filetype) actual.

**Returns:**
int - Un código hash para el actual objeto [FileType](../../com.groupdocs.merger.domain/filetype).
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Determina si dos objetos [FileType](../../com.groupdocs.merger.domain/filetype) son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Objeto [FileType] izquierdo. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Objeto [FileType] derecho. |

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

si ambos objetos [FileType](../../com.groupdocs.merger.domain/filetype) no son iguales; de lo contrario,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.

**Returns:**
java.lang.String - Una cadena que representa el objeto actual.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) de entrada es un formato de texto primitivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El objeto [FileType](../../com.groupdocs.merger.domain/filetype). |

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

si la entrada [FileType](../../com.groupdocs.merger.domain/filetype) es formato de archivo; de lo contrario,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Determina si el [FileType](../../com.groupdocs.merger.domain/filetype) de entrada es un formato de texto primitivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | El objeto [FileType](../../com.groupdocs.merger.domain/filetype). |

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

si la entrada [FileType](../../com.groupdocs.merger.domain/filetype) es formato de audio; de lo contrario,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
