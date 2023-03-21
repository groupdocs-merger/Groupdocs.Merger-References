---
title: FileType
second_title: GroupDocs.Merger voor .NET API-referentie
description: Vertegenwoordigt bestandstype. Biedt methoden om een lijst te verkrijgen van alle bestandstypen die worden ondersteund doorGroupDocs.Merger  detecteren bestandstype door extensie etc.
type: docs
weight: 100
url: /nl/net/groupdocs.merger.domain/filetype/
---
## FileType class

Vertegenwoordigt bestandstype. Biedt methoden om een lijst te verkrijgen van alle bestandstypen die worden ondersteund door**GroupDocs.Merger** , detecteren bestandstype door extensie etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Achtervoegsel bestandsnaam (inclusief de punt ".") bijv. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Bestandstypenaam bijv. "Microsoft Word-document". |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Wijst bestandsextensie toe aan bestandstype. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Bepaalt of de stroom[`FileType`](../filetype) is hetzelfde als gespecificeerd[`FileType`](../filetype) object. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Bepaalt of de stroom[`FileType`](../filetype) is hetzelfde als gespecificeerd object. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Retourneert de hash-code voor de huidige[`FileType`](../filetype) object. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Retourneert een tekenreeks die het huidige object vertegenwoordigt. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Haalt ondersteunde bestandstypen op |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Bepaalt of invoer[`FileType`](../filetype) is archiefformaat. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Bepaalt of invoer[`FileType`](../filetype) is afbeeldingsformaat. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Bepaalt of invoer[`FileType`](../filetype) is primitief tekstformaat. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Bepaalt of twee[`FileType`](../filetype) objecten zijn hetzelfde. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Bepaalt of twee[`FileType`](../filetype) objecten zijn niet hetzelfde. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap Image File (.bmp) vertegenwoordigt bestanden die worden gebruikt om digitale bitmapafbeeldingen op te slaan. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 gecomprimeerd bestand (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Bestand met door komma's gescheiden waarden (.csv) vertegenwoordigt platte tekstbestanden die gegevensrecords bevatten met door komma's gescheiden waarden. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word-document (.doc) vertegenwoordigt documenten die zijn gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binaire bestandsindeling. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm)-bestanden zijn Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML-document (.docx) is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, werd de structuur van dit nieuwe documentformaat gewijzigd van gewoon binair naar een combinatie van XML en binaire bestanden. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word-documentsjabloonbestanden (.dot) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf opgemaakte instellingen voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML-documentsjabloon (.dotx) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf opgemaakte instellingen voor het genereren van verdere DOCX-bestanden. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook-bestand (.epub) is een e-bookbestandsformaat dat een standaard digitaal publicatieformaat biedt voor uitgevers en consumenten. Het formaat is inmiddels zo gangbaar dat het door veel e-readers en softwaretoepassingen wordt ondersteund. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log File (.err) is een tekstbestand dat foutmeldingen bevat die door een programma zijn gegenereerd. Meer informatie over dit bestandsformaat[hier](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | Bestand in grafische uitwisselingsindeling (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip gecomprimeerd bestand (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) is de extensie voor webpagina's die zijn gemaakt voor weergave in browsers. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG-afbeelding (.jpeg) is een type afbeeldingsindeling die wordt opgeslagen met behulp van de methode van compressie met verlies. Het uitvoerbeeld, als resultaat van compressie, is een wisselwerking tussen opslaggrootte en beeldkwaliteit. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG-afbeelding (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML-webarchief (.mht) is een archiefindeling voor webpagina's die door een aantal verschillende toepassingen kan worden gemaakt. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML-bestand (.mhtml) is een archiefindeling voor webpagina's die door een aantal verschillende toepassingen kan worden gemaakt. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) vertegenwoordigt het presentatiebestandsformaat dat wordt gebruikt door OpenOffice.org in de OASISOpen-standaard. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument-tekstdocumentbestanden (.odt) zijn type documenten die zijn gemaakt met tekstverwerkingsprogramma's die zijn gebaseerd op de OpenDocument-tekstbestandsindeling. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote-documentbestanden (.one) worden gemaakt door de Microsoft OneNote-toepassing. Met OneNote kunt u informatie verzamelen met behulp van de toepassing alsof u uw kladblok gebruikt om aantekeningen te maken. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument-presentatiesjabloon (.otp) vertegenwoordigt presentatiesjabloonbestanden gemaakt door toepassingen in de OASIS OpenDocument-standaardindeling. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument-documentsjabloon (.ott) vertegenwoordigt sjabloondocumenten die zijn gegenereerd door toepassingen in overeenstemming met het OpenDocument-standaardformaat van OASIS. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) is een bestandsindeling die werd geïntroduceerd als een standaard voor weergave van documenten en ander referentiemateriaal in een indeling die onafhankelijk is van toepassingssoftware, hardware en het besturingssysteem. Meer informatie over dit bestand formaat[hier](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) is een type rasterafbeeldingsbestandsindeling die lossless compressie gebruikt. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint-diavoorstelling (.pps) is een bestand dat is gemaakt met Microsoft PowerPoint voor diavoorstellingen. Het lezen en maken van PPS-bestanden wordt ondersteund door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML-diavoorstelling (.ppsx) is een bestand dat is gemaakt met Microsoft PowerPoint 2007 en hoger voor diavoorstellingen. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint-presentatie (.ppt) vertegenwoordigt een PowerPoint-bestand dat bestaat uit een verzameling dia's voor weergave als SlideShow. Het specificeert de binaire bestandsindeling die wordt gebruikt door Microsoft PowerPoint 97-2003. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML-presentatie (.pptx) is een presentatiebestand dat is gemaakt met de populaire Microsoft PowerPoint-toepassing. In tegenstelling tot de vorige versie van het presentatiebestandsformaat PPT, dat binair was, is het PPTX-formaat gebaseerd op het Microsoft PowerPoint open XML-presentatiebestandsformaat. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript-bestand (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal Archief gecomprimeerd bestand (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format-bestand (.rtf), geïntroduceerd en gedocumenteerd door Microsoft, het Rich Text Format (RTF) vertegenwoordigt een methode voor het coderen van opgemaakte tekst en afbeeldingen voor gebruik in toepassingen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip gecomprimeerd bestand (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Geconsolideerd Unix-bestandsarchief (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX-brondocument (.tex) is een taal die zowel programmeer- als opmaakfuncties omvat en wordt gebruikt om documenten op te zetten. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | Tagged afbeeldingsbestand (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Tagged afbeeldingsbestandsindeling (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Bestand met door tabs gescheiden waarden (.tsv) vertegenwoordigt gegevens gescheiden door tabs in tekst zonder opmaak. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Platte tekstbestand (.txt) vertegenwoordigt een tekstdocument dat platte tekst bevat in de vorm van regels. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Vertegenwoordigt onbekend bestandstype. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML-bestand (.vdx) is een tekening of diagram gemaakt in Microsoft Visio, maar opgeslagen in XML-indeling met de extensie .VDX. Een Visio-tekening XML-bestand wordt gemaakt in Visio-software, die is ontwikkeld door Microsoft. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) zijn tekeningbestanden die zijn gemaakt met de Microsoft Visio-toepassing die macro's ondersteunt. VSDM-bestanden zijn OPC/XML-tekeningen die vergelijkbaar zijn met VSDX, maar die ook de mogelijkheid bieden om macro's uit te voeren wanneer het bestand wordt geopend. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio-tekening (.vsdx) vertegenwoordigt de Microsoft Visio-bestandsindeling die vanaf Microsoft Office 2013 is geïntroduceerd. Het is ontwikkeld ter vervanging van de binaire bestandsindeling .VSD, die wordt ondersteund door eerdere versies van Microsoft Visio. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) zijn Microsoft Visio Stencil-bestanden die ondersteuning bieden voor macro's. Wanneer een VSSM-bestand wordt geopend, kunnen de macro's worden uitgevoerd om de gewenste opmaak en plaatsing van vormen in een diagram te bereiken. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio-stencilbestand (.vssx) zijn tekenstencils die zijn gemaakt met Microsoft Visio 2013 en hoger. Het VSSX-bestandsformaat kan worden geopend met Visio 2013 en hoger. Visio-bestanden staan bekend om de weergave van verschillende tekenelementen, zoals verzameling vormen, connectoren, stroomschema's, netwerklay-out, UML-diagrammen, Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) zijn sjabloonbestanden gemaakt met Microsoft Visio die macro's ondersteunen. In tegenstelling tot VSDX-bestanden kunnen bestanden die zijn gemaakt op basis van VSTM-sjablonen macro's uitvoeren die zijn ontwikkeld in Visual Basic for Applications (VBA)-code. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio-tekeningsjabloon (.vstx) zijn tekeningsjabloonbestanden die zijn gemaakt met Microsoft Visio 2013 en hoger. Deze VSTX-bestanden bieden een startpunt voor het maken van Visio-tekeningen, opgeslagen als .VSDX-bestanden, met standaardlay-out en instellingen. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML-bestand (.vsx) verwijst naar stencils die bestaan uit tekeningen en vormen die worden gebruikt voor het maken van diagrammen in Microsoft Visio. VSX-bestanden worden opgeslagen in XML-bestandsindeling en werden ondersteund tot Visio 2013. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio-sjabloon XML-bestand (.vtx) is een Microsoft Visio-tekeningsjabloon die in XML-bestandsindeling op schijf wordt opgeslagen. De sjabloon is bedoeld om een bestand met basisinstellingen te bieden dat kan worden gebruikt om meerdere Visio-bestanden met dezelfde instellingen te maken. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel-invoegtoepassing met ingeschakelde macro's (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) is een bestand dat kan worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | De bestandsindeling Excel Binary Spreadsheet (.xlsb) specificeert de binaire bestandsindeling van Excel, een verzameling records en structuren die de inhoud van de Excel-werkmap specificeren. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) is een type Spreadsheet-bestanden dat macro's ondersteunt. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) is een bekende indeling voor Microsoft Excel-documenten die door Microsoft is geïntroduceerd met de release van Microsoft Office 2007. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel-sjabloonbestand (.xlt) zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT-bestanden en het openen ervan. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML-spreadsheetsjabloon met ingeschakelde macro's (.xltm) vertegenwoordigt bestanden die door Microsoft Excel zijn gegenereerd als sjabloonbestanden met ingeschakelde macro's. XLTM-bestanden lijken qua structuur op XLTX, behalve dat de laatste geen ondersteuning biedt voor het maken van sjabloonbestanden met macro's. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML Spreadsheet Template-bestanden (.xltx) zijn gebaseerd op de Office OpenXML-bestandsformaatspecificaties. Het wordt gebruikt om een standaard sjabloonbestand te maken dat kan worden gebruikt om XLSX-bestanden te genereren met dezelfde instellingen als gespecificeerd in het XLTX-bestand. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) vertegenwoordigt paginalay-outbestanden die zijn gebaseerd op XML Paper Specifications gemaakt door Microsoft. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | Gecomprimeerd bestand (.zip) |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over bestandsindelingen die worden ondersteund door GroupDocs.Merger: [Volledige lijst met ondersteunde documentindelingen](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Meer informatie over het verkrijgen van ondersteunde bestandstypen in code: [Hoe u ondersteunde bestandsindelingen in code kunt krijgen](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Zie ook

* naamruimte [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* montage [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
