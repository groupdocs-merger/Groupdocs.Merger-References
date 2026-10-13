---
title: "FileType"
second_title: "GroupDocs.Merger for Java API-referentie"
description: "Stelt bestandstype voor."
type: docs
weight: 10
url: /nl/java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Stelt een bestandstype voor. Biedt methoden om een lijst te verkrijgen van alle bestandstypen die worden ondersteund door **GroupDocs.Merger**, bestandstype te detecteren op basis van extensie enz.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Unknown](#Unknown) | Stelt een onbekend bestandstype voor. |
| [ZIP](#ZIP) | Gecomprimeerd bestand (.zip) |
| [SevenZ](#SevenZ) | 7-Zip gecomprimeerd bestand (.7z) |
| [TAR](#TAR) | Geconsolideerd Unix-bestandsarchief (.tar) |
| [RAR](#RAR) | Roshal ARchive gecomprimeerd bestand (.rar) |
| [VSSX](#VSSX) | Visio Stencil-bestand (.vssx) zijn tekenstencils gemaakt met Microsoft Visio 2013 en hoger. |
| [VSDX](#VSDX) | Visio-tekening (.vsdx) stelt het Microsoft Visio-bestandsformaat voor dat is geïntroduceerd vanaf Microsoft Office 2013. |
| [VSDM](#VSDM) | Visio macro-ondersteunde tekening (.vsdm) zijn tekenbestanden gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. |
| [VSTX](#VSTX) | Visio-tekeningssjabloon (.vstx) zijn sjabloonbestanden gemaakt met Microsoft Visio 2013 en hoger. |
| [VSTM](#VSTM) | Visio macro-ondersteunde tekeningssjabloon (.vstm) zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. |
| [VSSM](#VSSM) | Visio macro-ondersteund stencilbestand (.vssm) zijn Microsoft Visio-stencilbestanden die macro's ondersteunen. |
| [VSX](#VSX) | Visio Stencil XML-bestand (.vsx) verwijst naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. |
| [VTX](#VTX) | Visio sjabloon XML-bestand (.vtx) is een Microsoft Visio-tekeningssjabloon dat op schijf wordt opgeslagen in XML-bestandsformaat. |
| [VDX](#VDX) | Visio-tekening XML-bestand (.vdx) is een tekening of diagram gemaakt in Microsoft Visio, maar opgeslagen in XML-formaat met de .VDX-extensie. |
| [EPUB](#EPUB) | Open eBook-bestand (.epub) is een e‑book-bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. |
| [BMP](#BMP) | Bitmap‑afbeeldingsbestand (.bmp) vertegenwoordigt bestanden die worden gebruikt om bitmap‑digitale afbeeldingen op te slaan. |
| [JPG](#JPG) | JPEG‑afbeelding (.jpg) |
| [JPEG](#JPEG) | JPEG‑afbeelding (.jpeg) is een type afbeeldingsformaat dat wordt opgeslagen met behulp van verliesgevende compressie. |
| [PNG](#PNG) | Portable Network Graphic (.png) is een type rasterafbeeldingsformaat dat verliesloze compressie gebruikt. |
| [PS](#PS) | PostScript‑bestand (.ps) |
| [TIF](#TIF) | Tagged Image File (.tif) |
| [TIFF](#TIFF) | Tagged Image File Format (.tiff) |
| [GIF](#GIF) | Graphical Interchange Format File (.gif) |
| [SVG](#SVG) | Scalable Vector Graphics File (.svg) |
| [SVGZ](#SVGZ) | Scalable Vector Graphics Compressed File (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Hypertext Markup Language‑bestand (.html) is de extensie voor webpagina’s die zijn gemaakt voor weergave in browsers. |
| [MHT](#MHT) | MHTML‑webarchief (.mht) is een webpagina‑archiefformaat dat kan worden gemaakt door verschillende toepassingen. |
| [MHTML](#MHTML) | MIME‑HTML‑bestand (.mhtml) is een webpagina‑archiefformaat dat kan worden gemaakt door verschillende toepassingen. |
| [ONE](#ONE) | OneNote‑document (.one)‑bestanden worden gemaakt door de Microsoft OneNote‑applicatie. |
| [PDF](#PDF) | Portable Document Format‑bestand (.pdf) is een bestandsformaat dat werd geïntroduceerd als een standaard voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. |
| [XPS](#XPS) | XML Paper Specification‑bestand (.xps) vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications, gemaakt door Microsoft. |
| [TEX](#TEX) | LaTeX‑bronbestand (.tex) is een taal die programmeer- en opmaakfuncties omvat en wordt gebruikt om documenten op te maken. |
| [PPT](#PPT) | PowerPoint‑presentatie (.ppt) vertegenwoordigt een PowerPoint‑bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. |
| [PPTX](#PPTX) | PowerPoint Open XML‑presentatie (.pptx) is een presentatiedocument gemaakt met de populaire Microsoft PowerPoint‑applicatie. |
| [PPS](#PPS) | PowerPoint‑diavoorstelling (.pps) is een bestand dat is gemaakt met Microsoft PowerPoint voor het doel van een diavoorstelling. |
| [PPSX](#PPSX) | PowerPoint Open XML‑diavoorstelling (.ppsx) is een bestand dat is gemaakt met Microsoft PowerPoint 2007 en hoger voor het doel van een diavoorstelling. |
| [ODP](#ODP) | OpenDocument‑presentatie (.odp) vertegenwoordigt een presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org in de OASIS‑Open‑standaard. |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) vertegenwoordigt presentatiesjabloonbestanden die zijn gemaakt door toepassingen in het OASIS OpenDocument-standaardformaat. |
| [PPTM](#PPTM) | PowerPoint Open XML Macro-Enabled Presentatie |
| [XLS](#XLS) | Excel Spreadsheet (.xls) is een bestand dat kan worden gemaakt door Microsoft Excel, evenals andere soortgelijke spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) is een bekend formaat voor Microsoft Excel-documenten dat werd geïntroduceerd door Microsoft met de uitgave van Microsoft Office 2007. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is een type spreadsheetbestanden die macro's ondersteunen. |
| [XLSB](#XLSB) | Excel Binary Spreadsheet (.xlsb) bestandsformaat specificeert het Excel Binary File Format, dat een verzameling records en structuren is die de inhoud van een Excel-werkmap specificeren. |
| [CSV](#CSV) | Comma Separated Values File (.csv) vertegenwoordigt platte tekstbestanden die records met gegevens bevatten met door komma's gescheiden waarden. |
| [TSV](#TSV) | Tab Separated Values File (.tsv) vertegenwoordigt gegevens die met tabs gescheiden zijn in een platte-tekstformaat. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods). |
| [XLTM](#XLTM) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) vertegenwoordigt bestanden die worden gegenereerd door Microsoft Excel als macro-ingeschakelde sjabloonbestanden. |
| [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) bestanden zijn gebaseerd op de Office OpenXML bestandsformaat-specificaties. |
| [XLT](#XLT) | Excel Template File (.xlt) zijn sjabloonbestanden gemaakt met Microsoft Excel, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. |
| [XLAM](#XLAM) | Excel Macro-Enabled Add-In (.xlam). |
| [DOC](#DOC) | Microsoft Word Document (.doc) vertegenwoordigt documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binair bestandsformaat. |
| [DOCX](#DOCX) | Microsoft Word Open XML Document (.docx) is een bekend formaat voor Microsoft Word-documenten. |
| [DOCM](#DOCM) | Word Open XML Macro-Enabled Document (.docm) bestanden zijn documenten die zijn gegenereerd door Microsoft Word 2007 of hoger en de mogelijkheid hebben macro's uit te voeren. |
| [DOT](#DOT) | Word Document Template (.dot) bestanden zijn sjabloonbestanden gemaakt door Microsoft Word om vooraf opgemaakte instellingen te hebben voor het genereren van verdere DOC- of DOCX-bestanden. |
| [DOTX](#DOTX) | Word Open XML Document Template (.dotx) zijn sjabloonbestanden gemaakt door Microsoft Word om vooraf opgemaakte instellingen te hebben voor het genereren van verdere DOCX-bestanden. |
| [DOTM](#DOTM) | Word Open XML Macro-Enabled Document Template (.dotm) vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger. |
| [RTF](#RTF) | Rich Text Format File (.rtf) geïntroduceerd en gedocumenteerd door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en grafische elementen te coderen voor gebruik binnen toepassingen. |
| [TXT](#TXT) | Plain Text File (.txt) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. |
| [ERR](#ERR) | Error Log File (.err) is een tekstbestand dat foutmeldingen bevat die door een programma zijn gegenereerd. |
| [ODT](#ODT) | OpenDocument Text Document (.odt) bestanden zijn een type documenten die zijn gemaakt met tekstverwerkingsapplicaties die gebaseerd zijn op het OpenDocument Text File-formaat. |
| [OTT](#OTT) | OpenDocument Document Template (.ott) vertegenwoordigt sjabloondocumenten die zijn gegenereerd door toepassingen in overeenstemming met het OpenDocument-standaardformaat van OASIS. |
| [WAV](#WAV) | WAV, bekend als WAVE (Waveform Audio File Format), is een subset van Microsoft\u2019s Resource Interchange File Format (RIFF) specificatie voor het opslaan van digitale audiobestanden. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bestandstype naam bijv. |
| [getExtension()](#getExtension--) | Bestandsnaamextensie (inclusief de punt ".") bijv. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Koppelt bestandsnaamextensie aan bestandstype. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Haalt ondersteunde bestandstypen op |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Bepaalt of het huidige [FileType](../../com.groupdocs.merger.domain/filetype) hetzelfde is als het opgegeven [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of het huidige [FileType](../../com.groupdocs.merger.domain/filetype) hetzelfde is als het opgegeven object. |
| [hashCode()](#hashCode--) | Retourneert de hashcode voor het huidige [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Bepaalt of twee [FileType](../../com.groupdocs.merger.domain/filetype) objecten hetzelfde zijn. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Bepaalt of twee [FileType](../../com.groupdocs.merger.domain/filetype) objecten niet hetzelfde zijn. |
| [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Bepaalt of de invoer [FileType](../../com.groupdocs.merger.domain/filetype) een primitief tekstformaat is. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Bepaalt of de invoer [FileType](../../com.groupdocs.merger.domain/filetype) een archiefformaat is. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Bepaalt of de invoer [FileType](../../com.groupdocs.merger.domain/filetype) een primitief tekstformaat is. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Bepaalt of de invoer [FileType](../../com.groupdocs.merger.domain/filetype) een audioformaat is. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Stelt een onbekend bestandstype voor.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Gecomprimeerd bestand (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


7-Zip gecomprimeerd bestand (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Geconsolideerd Unix-bestandsarchief (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal ARchive gecomprimeerd bestand (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil-bestand (.vssx) zijn tekenstencils gemaakt met Microsoft Visio 2013 en hoger. Het VSSX-bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio-bestanden staan bekend om de weergave van diverse tekenelementen zoals een verzameling vormen, connectoren, stroomdiagrammen, netwerklay-outs, UML-diagrammen. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio-tekening (.vsdx) vertegenwoordigt het Microsoft Visio-bestandsformaat dat vanaf Microsoft Office 2013 is geïntroduceerd. Het is ontwikkeld om het binaire bestandsformaat .VSD te vervangen, dat wordt ondersteund door eerdere versies van Microsoft Visio. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio macro-ondersteunde tekening (.vsdm) zijn tekenbestanden gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. VSDM-bestanden zijn OPC/XML-tekeningen die vergelijkbaar zijn met VSDX, maar ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio-tekeningtemplate (.vstx) zijn tekensjabloonbestanden gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX-bestanden bieden een startpunt voor het maken van Visio-tekeningen, opgeslagen als .VSDX-bestanden, met een standaardlay-out en instellingen. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio macro-ondersteunde tekensjabloon (.vstm) zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. In tegenstelling tot VSDX-bestanden kunnen bestanden die zijn gemaakt vanuit VSTM-sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio macro-ondersteund stencilbestand (.vssm) zijn Microsoft Visio-stencilbestanden die ondersteuning voor macro's bieden. Een VSSM-bestand maakt bij openen het mogelijk om macro's uit te voeren om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio stencil XML-bestand (.vsx) verwijst naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX-bestanden worden opgeslagen in XML-bestandsformaat en werden ondersteund tot Visio 2013. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio sjabloon XML-bestand (.vtx) is een Microsoft Visio-teken-sjabloon die op schijf wordt opgeslagen in XML-bestandsformaat. Het sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio-bestanden met dezelfde instellingen te maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio-tekening XML-bestand (.vdx) is een tekening of diagram gemaakt in Microsoft Visio, maar opgeslagen in XML-formaat met de .VDX-extensie. Een Visio-tekening XML-bestand wordt gemaakt in Visio-software, die is ontwikkeld door Microsoft. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook-bestand (.epub) is een e-book-bestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. Het formaat is inmiddels zo gangbaar dat het wordt ondersteund door veel e-readers en softwaretoepassingen. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) vertegenwoordigt bestanden die worden gebruikt om bitmap digitale afbeeldingen op te slaan. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG‑afbeelding (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) is een type afbeeldingsformaat dat wordt opgeslagen met behulp van verliesgevende compressie. De uitvoerafbeelding, als resultaat van de compressie, is een afweging tussen opslaggrootte en beeldkwaliteit. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) is een type rasterafbeeldingsformaat dat verliesloze compressie gebruikt. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript‑bestand (.ps)

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


Hypertext Markup Language File (.html) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) is een webpagina-archiefformaat dat kan worden gemaakt door een aantal verschillende applicaties. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) is een webpagina-archiefformaat dat kan worden gemaakt door een aantal verschillende applicaties. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote Document (.one) bestanden worden gemaakt door de Microsoft OneNote-applicatie. OneNote stelt je in staat om informatie te verzamelen met de applicatie alsof je je kladblok gebruikt om aantekeningen te maken. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format File (.pdf) is een bestandsformaat dat werd geïntroduceerd als een standaard voor de weergave van documenten en ander referentiemateriaal in een formaat dat onafhankelijk is van toepassingssoftware, hardware en besturingssysteem. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification File (.xps) vertegenwoordigt paginalay-outbestanden die gebaseerd zijn op XML Paper Specifications gemaakt door Microsoft. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX Source Document (.tex) is een taal die bestaat uit programmeer- en opmaakfuncties, gebruikt om documenten op te maken. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint Presentation (.ppt) vertegenwoordigt een PowerPoint-bestand dat bestaat uit een verzameling dia's voor weergave als diavoorstelling. Het specificeert het binaire bestandsformaat dat wordt gebruikt door Microsoft PowerPoint 97-2003. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML Presentation (.pptx) is een presentatiedocument gemaakt met de populaire Microsoft PowerPoint-applicatie. In tegenstelling tot de vorige versie van het presentatiedocumentformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het open XML-presentatieformaat van Microsoft PowerPoint. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint Slide Show (.pps) is een bestand dat is gemaakt met Microsoft PowerPoint voor diavoorstellingsdoeleinden. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML Slide Show (.ppsx) is een bestand dat is gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingsdoeleinden. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument Presentation (.odp) vertegenwoordigt het presentatiedocumentformaat dat wordt gebruikt door OpenOffice.org in de OASIS Open-standaard. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) vertegenwoordigt presentatiesjabloonbestanden die zijn gemaakt door applicaties in het OASIS OpenDocument-standaardformaat. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/presentation/otp

### PPTM {#PPTM}
```
public static FileType PPTM
```


PowerPoint Open XML Macro-Enabled Presentatie

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) is een bestand dat kan worden gemaakt door Microsoft Excel evenals andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) is een bekend formaat voor Microsoft Excel-documenten dat werd geïntroduceerd door Microsoft met de release van Microsoft Office 2007. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is een type spreadsheetbestanden die macro's ondersteunen. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Excel Binary Spreadsheet (.xlsb) bestandsformaat specificeert het Excel Binary File Format, dat een verzameling records en structuren is die de inhoud van een Excel-werkmap specificeren. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) vertegenwoordigt platte tekstbestanden die records van gegevens met door komma's gescheiden waarden bevatten. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) vertegenwoordigt gegevens die met tabs gescheiden zijn in een platte-tekstformaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro-ondersteunde sjabloonbestanden. XLTM-bestanden lijken op XLTX in structuur, behalve dat de laatste geen sjabloonbestanden met macro's kan maken. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx) bestanden zijn gebaseerd op de Office OpenXML bestandsformaatspecificaties. Ze worden gebruikt om een standaard sjabloonbestand te maken dat kan worden gebruikt om XLSX-bestanden te genereren die dezelfde instellingen vertonen als gespecificeerd in het XLTX-bestand. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt) zijn sjabloonbestanden die met Microsoft Excel zijn gemaakt, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT-bestanden en het openen ervan. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel Macro-Enabled Add-In (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) vertegenwoordigt documenten die door Microsoft Word of andere tekstverwerkingsprogramma's zijn gegenereerd in binair bestandsformaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van platte binair naar een combinatie van XML- en binaire bestanden. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) bestanden zijn door Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) bestanden zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt om vooraf geformatteerde instellingen te hebben voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) vertegenwoordigt een sjabloonbestand dat is gemaakt met Microsoft Word 2007 of hoger. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf) geïntroduceerd en gedocumenteerd door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode om opgemaakte tekst en grafische elementen te coderen voor gebruik in applicaties. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt) vertegenwoordigt een tekstdocument dat platte tekst in de vorm van regels bevat. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Error Log File (.err) is een tekstbestand dat foutmeldingen bevat die door een programma zijn gegenereerd. Meer informatie over dit bestandsformaat [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) bestanden zijn een type documenten die met tekstverwerkingsapplicaties zijn gemaakt en gebaseerd zijn op het OpenDocument Text File-formaat. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) vertegenwoordigt sjabloondocumenten die door applicaties worden gegenereerd in overeenstemming met het OpenDocument-standaardformaat van OASIS. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, bekend als WAVE (Waveform Audio File Format), is een subset van Microsoft’s Resource Interchange File Format (RIFF) specificatie voor het opslaan van digitale audiobestanden. Het formaat past geen compressie toe op de bitstroom en slaat de audio-opnames op met verschillende bemonsteringsfrequenties en bitrates. Het is al lange tijd een van de standaardformaten voor audio‑cd’s. Meer informatie over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Bestandstype naam bijv. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Bestandnaam achtervoegsel (inclusief de punt ".") bijv. ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Koppelt bestandsnaamextensie aan bestandstype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extensie | java.lang.String | Bestandsextensie (inclusief de punt "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Haalt ondersteunde bestandstypen op

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Retourneert een reeks ondersteunde bestandstypen
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Bepaalt of het huidige [FileType](../../com.groupdocs.merger.domain/filetype) hetzelfde is als het opgegeven [FileType](../../com.groupdocs.merger.domain/filetype) object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | Het object om te vergelijken met het huidige [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

als

```
obj
```

parameter is [FileType](../../com.groupdocs.merger.domain/filetype) en is hetzelfde als het huidige [FileType](../../com.groupdocs.merger.domain/filetype) object; anders,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Retourneert de hashcode voor het huidige [FileType](../../com.groupdocs.merger.domain/filetype) object.

**Returns:**
int - Een hashcode voor het huidige [FileType](../../com.groupdocs.merger.domain/filetype) object.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Bepaalt of twee [FileType](../../com.groupdocs.merger.domain/filetype) objecten hetzelfde zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Linker [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Rechter [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

als beide [FileType](../../com.groupdocs.merger.domain/filetype) objecten niet hetzelfde zijn; anders,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.

**Returns:**
java.lang.String - Een string die het huidige object representeert.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Bepaalt of de invoer [FileType](../../com.groupdocs.merger.domain/filetype) een primitief tekstformaat is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

als invoer [FileType](../../com.groupdocs.merger.domain/filetype) een archiefformaat is; anders,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Bepaalt of de invoer [FileType](../../com.groupdocs.merger.domain/filetype) een primitief tekstformaat is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Het [FileType](../../com.groupdocs.merger.domain/filetype) object. |

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

als invoer [FileType](../../com.groupdocs.merger.domain/filetype) een audioformaat is; anders,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
