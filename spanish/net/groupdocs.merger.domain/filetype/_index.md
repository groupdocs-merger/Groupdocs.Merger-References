---
title: FileType
second_title: Referencia de API de GroupDocs.Merger para .NET
description: Representa el tipo de archivo. Proporciona métodos para obtener una lista de todos los tipos de archivos admitidos porGroupDocs.Merger  detecta el tipo de archivo por extensión etc.
type: docs
weight: 100
url: /es/net/groupdocs.merger.domain/filetype/
---
## FileType class

Representa el tipo de archivo. Proporciona métodos para obtener una lista de todos los tipos de archivos admitidos por**GroupDocs.Merger** , detecta el tipo de archivo por extensión, etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Sufijo de nombre de archivo (incluido el punto "."), por ejemplo, ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nombre del tipo de archivo, por ejemplo, "Documento de Microsoft Word". |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Asigna la extensión del archivo al tipo de archivo. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Determina si la corriente[`FileType`](../filetype) es igual a lo especificado[`FileType`](../filetype) objeto. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Determina si la corriente[`FileType`](../filetype) es el mismo que el objeto especificado. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Devuelve el código hash para el actual[`FileType`](../filetype) objeto. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Devuelve una cadena que representa el objeto actual. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Recupera tipos de archivo admitidos |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Determina si la entrada[`FileType`](../filetype) es formato de archivo. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Determina si la entrada[`FileType`](../filetype) es formato de imagen. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Determina si la entrada[`FileType`](../filetype) es formato de texto primitivo. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Determina si dos[`FileType`](../filetype) los objetos son iguales. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Determina si dos[`FileType`](../filetype) los objetos no son iguales. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Archivo de imagen de mapa de bits (.bmp) representa archivos que se utilizan para almacenar imágenes digitales de mapa de bits. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Archivo comprimido Bzip2 (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | El archivo de valores separados por comas (.csv) representa archivos de texto sin formato que contienen registros de datos con valores separados por comas. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Documento de Microsoft Word (.doc) representa documentos generados por Microsoft Word u otros documentos de procesamiento de textos en formato de archivo binario. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Los archivos Word Open XML Macro-Enabled Document (.docm) son documentos generados por Microsoft Word 2007 o superior con la capacidad de ejecutar macros. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | El documento XML abierto de Microsoft Word (.docx) es un formato muy conocido para los documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento se cambió de binario simple a una combinación de XML y archivos binarios. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Los archivos de plantilla de documento de Word (.dot) son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de más archivos DOC o DOCX. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Plantilla de documento de Word Open XML habilitado para macros (.dotm) representa un archivo de plantilla creado con Microsoft Word 2007 o superior. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Plantilla de documento XML abierto de Word (.dotx) son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de más archivos DOCX. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) es un formato de archivo de libro electrónico que proporciona un formato de publicación digital estándar para editores y consumidores. El formato ya es tan común que es compatible con muchos lectores electrónicos y aplicaciones de software. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | El archivo de registro de errores (.err) es un archivo de texto que contiene mensajes de error generados por un programa. Más información sobre este formato de archivo[aquí](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | Archivo de formato de intercambio gráfico (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | Archivo comprimido G-Zip (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | El archivo de lenguaje de marcado de hipertexto (.html) es la extensión para las páginas web creadas para mostrarse en los navegadores. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | Imagen JPEG (.jpeg) es un tipo de formato de imagen que se guarda mediante el método de compresión con pérdida. La imagen de salida, como resultado de la compresión, es una compensación entre el tamaño de almacenamiento y la calidad de la imagen. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | Imagen JPEG (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) es un formato de archivo de página web que pueden crear varias aplicaciones diferentes. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) es un formato de archivo de página web que pueden crear varias aplicaciones diferentes. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) representa el formato de archivo de presentación utilizado por OpenOffice.org en el estándar OASISOpen. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | Hoja de cálculo de OpenDocument (.ods) Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | Los archivos de documento de texto OpenDocument (.odt) son un tipo de documentos creados con aplicaciones de procesamiento de textos que se basan en el formato de archivo de texto OpenDocument. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | Los archivos de documento de OneNote (.one) son creados por la aplicación Microsoft OneNote. OneNote le permite recopilar información usando la aplicación como si estuviera usando su bloc de notas para tomar notas. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | Plantilla de presentación de OpenDocument (.otp) representa archivos de plantilla de presentación creados por aplicaciones en formato estándar OASIS OpenDocument. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | Plantilla de documento OpenDocument (.ott) representa documentos de plantilla generados por aplicaciones de conformidad con el formato estándar OpenDocument de OASIS. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | El archivo de formato de documento portátil (.pdf) es un formato de archivo que se introdujo como estándar para la representación de documentos y otro material de referencia en un formato que es independiente del software de la aplicación, el hardware y el sistema operativo. Más información sobre este archivo formato[aquí](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Gráfico de red portátil (.png) es un tipo de formato de archivo de imagen de trama que utiliza compresión sin pérdidas. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | Presentación de diapositivas de PowerPoint (.pps) es un archivo creado con Microsoft PowerPoint para fines de presentación de diapositivas. La lectura y creación de archivos PPS es compatible con Microsoft PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) es un archivo creado con Microsoft PowerPoint 2007 y superior para el propósito de presentación de diapositivas. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | Presentación de PowerPoint (.ppt) representa un archivo de PowerPoint que consta de una colección de diapositivas para mostrarlas como presentación de diapositivas. Especifica el formato de archivo binario utilizado por Microsoft PowerPoint 97-2003. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) es un archivo de presentación creado con la popular aplicación Microsoft PowerPoint. A diferencia de la versión anterior del formato de archivo de presentación PPT, que era binario, el formato PPTX se basa en el formato de archivo de presentación XML abierto de Microsoft PowerPoint. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | Archivo PostScript (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Archivo comprimido Roshal ARchive (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Archivo de formato de texto enriquecido (.rtf) introducido y documentado por Microsoft, el formato de texto enriquecido (RTF) representa un método de codificación de texto y gráficos con formato para su uso dentro de las aplicaciones. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | Archivo comprimido 7-Zip (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Archivo de archivo Unix consolidado (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Source Document (.tex) es un lenguaje que se compone de funciones de programación y marcado, que se utiliza para componer documentos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | Archivo de imagen etiquetado (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Formato de archivo de imagen etiquetada (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | El archivo de valores separados por tabulaciones (.tsv) representa datos separados por tabulaciones en formato de texto sin formato. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Archivo de texto sin formato (.txt) representa un documento de texto que contiene texto sin formato en forma de líneas. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Representa un tipo de archivo desconocido. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | El archivo XML de dibujo de Visio (.vdx) es un dibujo o gráfico creado en Microsoft Visio, pero guardado en formato XML con extensión .VDX. Se crea un archivo XML de dibujo de Visio en el software Visio, desarrollado por Microsoft. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Los dibujos habilitados para macros de Visio (.vsdm) son archivos de dibujo creados con la aplicación Microsoft Visio que admite macros. Los archivos VSDM son dibujos OPC/XML que son similares a VSDX, pero también brindan la capacidad de ejecutar macros cuando se abre el archivo. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) representa el formato de archivo de Microsoft Visio introducido desde Microsoft Office 2013 en adelante. Fue desarrollado para reemplazar el formato de archivo binario, .VSD, que es compatible con versiones anteriores de Microsoft Visio. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) son archivos de Microsoft Visio Stencil que admiten macros. Cuando se abre un archivo VSSM, permite ejecutar las macros para lograr el formato y la ubicación deseados de las formas en un diagrama. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) son plantillas de dibujo creadas con Microsoft Visio 2013 y superior. El formato de archivo VSSX se puede abrir con Visio 2013 y superior. Los archivos de Visio son conocidos por la representación de una variedad de elementos de dibujo, como la colección de formas, conectores, diagramas de flujo, diseño de red, diagramas UML, Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Plantilla de dibujo habilitada para macros de Visio (.vstm) son archivos de plantilla creados con Microsoft Visio que admiten macros. A diferencia de los archivos VSDX, los archivos creados a partir de plantillas VSTM pueden ejecutar macros desarrolladas en código Visual Basic para aplicaciones (VBA). Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Plantilla de dibujo de Visio (.vstx) son archivos de plantilla de dibujo creados con Microsoft Visio 2013 y superior. Estos archivos VSTX proporcionan un punto de partida para crear dibujos de Visio, guardados como archivos .VSDX, con diseño y configuración predeterminados. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) hace referencia a las plantillas que constan de dibujos y formas que se utilizan para crear diagramas en Microsoft Visio. Los archivos VSX se guardan en formato de archivo XML y fueron compatibles hasta Visio 2013. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | El archivo XML de plantilla de Visio (.vtx) es una plantilla de dibujo de Microsoft Visio que se guarda en un disco en formato de archivo XML. El objetivo de la plantilla es proporcionar un archivo con la configuración básica que se puede usar para crear varios archivos de Visio con la misma configuración. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Complemento habilitado para macros de Excel (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Hoja de cálculo de Excel (.xls) es un archivo que puede crear Microsoft Excel, así como otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | El formato de archivo de hoja de cálculo binaria de Excel (.xlsb) especifica el formato de archivo binario de Excel, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) es un tipo de archivo de hoja de cálculo que admite macros. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) es un formato muy conocido para documentos de Microsoft Excel que Microsoft introdujo con el lanzamiento de Microsoft Office 2007. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | El archivo de plantilla de Excel (.xlt) son archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo que forma parte del paquete Microsoft Office. Microsoft Office 97-2003 admitía la creación de nuevos archivos XLT y su apertura. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Plantilla de hoja de cálculo Excel Open XML habilitada para macros (.xltm) representa archivos generados por Microsoft Excel como archivos de plantilla habilitada para macros. Los archivos XLTM son similares a XLTX en estructura, excepto que el último no admite la creación de archivos de plantilla con macros. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Los archivos de plantilla de hoja de cálculo XML abierta de Excel (.xltx) se basan en las especificaciones de formato de archivo OpenXML de Office. Se utiliza para crear un archivo de plantilla estándar que se puede utilizar para generar archivos XLSX que muestren la misma configuración que se especifica en el archivo XLTX. Obtenga más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | El archivo de especificación de papel XML (.xps) representa archivos de diseño de página que se basan en las especificaciones de papel XML creadas por Microsoft. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | Archivo comprimido (.zip) |

### Observaciones

**Aprende más**

* Más información sobre los formatos de archivo compatibles con GroupDocs.Merger: [Lista completa de formatos de documentos admitidos](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Obtenga más información sobre cómo obtener tipos de archivos admitidos en el código: [Cómo obtener formatos de archivo compatibles en el código](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Ver también

* espacio de nombres [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* asamblea [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
