---
title: FileType
second_title: GroupDocs.Merger för .NET API-referens
description: Representerar filtyp. Ger metoder för att få en lista över alla filtyper som stöds avGroupDocs.Merger  detektera filtyp genom tillägg etc.
type: docs
weight: 100
url: /sv/net/groupdocs.merger.domain/filetype/
---
## FileType class

Representerar filtyp. Ger metoder för att få en lista över alla filtyper som stöds av**GroupDocs.Merger** , detektera filtyp genom tillägg etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Filnamnssuffix (inklusive perioden ".") t.ex. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Filtypsnamn t.ex. "Microsoft Word Document". |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Mappar filtillägget till filtyp. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Bestämmer om strömmen[`FileType`](../filetype) är samma som specificerat[`FileType`](../filetype) objekt. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Bestämmer om strömmen[`FileType`](../filetype) är samma som specificerat objekt. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Returnerar hashkoden för den aktuella[`FileType`](../filetype) objekt. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Hämtar filtyper som stöds |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Bestämmer om ingång[`FileType`](../filetype) är primitivt textformat. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Bestämmer om ingång[`FileType`](../filetype) är primitivt textformat. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Bestämmer om två[`FileType`](../filetype) objekten är desamma. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Bestämmer om två[`FileType`](../filetype) objekt är inte samma sak. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Comma Separated Values File (.csv) representerar vanliga textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word-dokument (.doc) representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm) filer är Microsoft Word 2007 eller högre genererade dokument med möjlighet att köra makron. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) är ett välkänt format för Microsoft Word-dokument. Introducerad från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från vanligt binärt till en kombination av XML och binära filer. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word-dokumentmallfiler (.dot) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) representerar mallfil skapad med Microsoft Word 2007 eller högre. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) är ett e-boksfilformat som tillhandahåller ett standardformat för digitala publikationer för förlag och konsumenter. Formatet har varit så vanligt vid det här laget att det stöds av många e-läsare och program. Läs mer om detta filformat[här](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Felloggfil (.err) är en textfil som innehåller felmeddelanden som genereras av ett program. Läs mer om detta filformat[här](https://fileinfo.com/extension/err) . |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) är tillägget för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat[här](https://docs.fileformat.com/web/html) . |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) är ett webbsidearkivformat som kan skapas av ett antal olika applikationer. Läs mer om detta filformat[här](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML-fil (.mhtml) är ett webbsidearkivformat som kan skapas av ett antal olika applikationer. Läs mer om detta filformat[här](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) representerar presentationsfilformat som används av OpenOffice.org i OASISOpen-standarden. Läs mer om detta filformat[här](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument Text Document (.odt)-filer är typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Text File-format. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote-dokumentfiler (.one) skapas av Microsoft OneNote-applikationen. OneNote låter dig samla in information med applikationen som om du använder din kladdplatta för att göra anteckningar. Läs mer om detta filformat[här](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument Presentation Template (.otp) representerar presentationsmallfiler skapade av applikationer i OASIS OpenDocument standardformat. Läs mer om detta filformat[här](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Document Template (.ott) representerar malldokument som genereras av applikationer i enlighet med OASIS OpenDocument-standardformat. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) är ett filformat som skulle introduceras som en standard för representation av dokument och annat referensmaterial i ett format som är oberoende av applikationsprogramvara, hårdvara samt operativsystem. Läs mer om den här filen formatera[här](https://docs.fileformat.com/view/pdf) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) är en fil skapad med Microsoft PowerPoint för Slide Show-ändamål. PPS-filläsning och skapande stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) är en fil skapad med Microsoft PowerPoint 2007 och senare för Slide Show-ändamål. Läs mer om detta filformat[här](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint-presentation (.ppt) representerar en PowerPoint-fil som består av en samling bilder för visning som bildspel. Den anger det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) är en presentationsfil skapad med det populära Microsoft PowerPoint-programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML-presentationsfilformat. Läs mer om detta filformat[här](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript-fil (.ps) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) introducerad och dokumenterad av Microsoft, Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/rtf) . |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX källdokument (.tex) är ett språk som består av både programmerings- och uppmärkningsfunktioner, som används för att sätta in dokument. Läs mer om detta filformat[här](https://docs.fileformat.com/page-description-language/tex) . |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tab Separated Values File (.tsv) representerar data separerade med flikar i vanligt textformat. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Vanlig textfil (.txt) representerar ett textdokument som innehåller ren text i form av rader. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Representerar okänd filtyp. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) är en ritning eller ett diagram som skapats i Microsoft Visio, men som sparats i XML-format har filtillägget .VDX. En Visio-ritnings-XML-fil skapas i Visio-programvaran, som är utvecklad av Microsoft. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) är ritfiler som skapats med Microsoft Visio-programmet som stöder makron. VSDM-filer är OPC/XML-ritningar som liknar VSDX, men som också ger möjlighet att köra makron när filen öppnas. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) representerar Microsoft Visio-filformat som introducerats från Microsoft Office 2013 och framåt. Det utvecklades för att ersätta det binära filformatet .VSD, som stöds av tidigare versioner av Microsoft Visio. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) är Microsoft Visio Stencil-filer som stöder ger stöd för makron. En VSSM-fil när den öppnas gör det möjligt att köra makron för att uppnå önskad formatering och placering av former i ett diagram. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) är ritstenciler skapade med Microsoft Visio 2013 och senare. VSSX-filformatet kan öppnas med Visio 2013 och högre. Visio-filer är kända för representation av en mängd olika ritningselement som samling av former, kopplingar, flödesscheman, nätverkslayout, UML-diagram, Läs mer om detta filformat[här](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) är mallfiler skapade med Microsoft Visio som stöder makron. Till skillnad från VSDX-filer kan filer skapade från VSTM-mallar köra makron som är utvecklade i Visual Basic for Applications (VBA)-kod. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) är ritmallsfiler skapade med Microsoft Visio 2013 och senare. Dessa VSTX-filer ger en startpunkt för att skapa Visio-ritningar, sparade som .VSDX-filer, med standardlayout och inställningar. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) hänvisar till schabloner som består av ritningar och former som används för att skapa diagram i Microsoft Visio. VSX-filer sparas i XML-filformat och stöddes till Visio 2013. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) är en Microsoft Visio ritmall som sparas på skiva i XML-filformat. Mallen syftar till att tillhandahålla en fil med grundläggande inställningar som kan användas för att skapa flera Visio-filer med samma inställningar. Läs mer om detta filformat[här](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel Macro-Enabled Add-In (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) är en fil som kan skapas av Microsoft Excel såväl som andra liknande kalkylbladsprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Filformatet Excel Binary Spreadsheet (.xlsb) anger det binära Excel-filformatet, som är en samling poster och strukturer som anger innehållet i Excel-arbetsboken. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML-kalkylblad (.xlsx) är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft i och med lanseringen av Microsoft Office 2007. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) är mallfiler skapade med Microsoft Excel som är ett kalkylbladsprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dessa. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Mall (.xltm) representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer liknar XLTX i annan struktur än att de senare inte stöder att skapa mallfiler med makron. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML Spreadsheet Template-filer (.xltx) är baserade på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som uppvisar samma inställningar som anges i XLTX-filen. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) representerar sidlayoutfiler som är baserade på XML Paper Specifications skapade av Microsoft. Läs mer om detta filformat[här](https://docs.fileformat.com/page-description-language/xps) . |

### Anmärkningar

**Läs mer**

* Läs mer om filformat som stöds av GroupDocs.Merger: [Fullständig lista över dokumentformat som stöds](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Läs mer om hur du får filtyper som stöds i kod: [Hur man får stödda filformat i kod](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Se även

* namnutrymme [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* hopsättning [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
