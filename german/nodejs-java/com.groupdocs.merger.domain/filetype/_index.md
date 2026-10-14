---
title: "FileType"
second_title: "GroupDocs.Merger für Node.js via Java API-Referenz"
description: "Stellt den Dateityp dar."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Stellt den Dateityp dar. Stellt Methoden bereit, um eine Liste aller von **GroupDocs.Merger** unterstützten Dateitypen zu erhalten, den Dateityp anhand der Erweiterung zu erkennen usw.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Unknown](#Unknown) | Stellt einen unbekannten Dateityp dar. |
| [ZIP](#ZIP) | Gezippte Datei (.zip) |
| [SevenZ](#SevenZ) | 7-Zip komprimierte Datei (.7z) |
| [TAR](#TAR) | Konsolidiertes Unix-Dateiarchiv (.tar) |
| [RAR](#RAR) | Roshal-Archiv komprimierte Datei (.rar) |
| [VSSX](#VSSX) | Visio-Stencil-Datei (.vssx) sind Zeichenvorlagen, die mit Microsoft Visio 2013 und höher erstellt wurden. |
| [VSDX](#VSDX) | Visio-Zeichnung (.vsdx) stellt das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. |
| [VSDM](#VSDM) | Visio-Makro‑aktivierte Zeichnung (.vsdm) sind Zeichnungsdateien, die mit der Microsoft Visio‑Anwendung erstellt wurden, die Makros unterstützt. |
| [VSTX](#VSTX) | Visio-Zeichnungsvorlage (.vstx) sind Vorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. |
| [VSTM](#VSTM) | Visio-Makro‑aktivierte Zeichnungsvorlage (.vstm) sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. |
| [VSSM](#VSSM) | Visio-Makro‑aktivierte Stencil-Datei (.vssm) sind Microsoft Visio‑Stencil‑Dateien, die Unterstützung für Makros bieten. |
| [VSX](#VSX) | Visio-Stencil-XML-Datei (.vsx) bezieht sich auf Stencils, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. |
| [VTX](#VTX) | Visio-Vorlagen‑XML-Datei (.vtx) ist eine Microsoft Visio‑Zeichnungsvorlage, die auf der Festplatte im XML-Dateiformat gespeichert wird. |
| [VDX](#VDX) | Visio-Zeichnungs‑XML-Datei (.vdx) ist eine in Microsoft Visio erstellte Zeichnung oder Grafik, die jedoch im XML-Format mit der Erweiterung .VDX gespeichert wird. |
| [EPUB](#EPUB) | Open-eBook-Datei (.epub) ist ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Leser bereitstellt. |
| [BMP](#BMP) | Bitmap-Bilddatei (.bmp) stellt Dateien dar, die zum Speichern von Bitmap‑Digitalbildern verwendet werden. |
| [JPG](#JPG) | JPEG-Bild (.jpg) |
| [JPEG](#JPEG) | JPEG-Bild (.jpeg) ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. |
| [PNG](#PNG) | Portable Network Graphic (.png) ist ein Rasterbilddateiformat, das verlustfreie Kompression verwendet. |
| [PS](#PS) | PostScript-Datei (.ps) |
| [TIF](#TIF) | Getaggte Bilddatei (.tif) |
| [TIFF](#TIFF) | Getaggtes Bilddateiformat (.tiff) |
| [GIF](#GIF) | Grafik-Austauschformat-Datei (.gif) |
| [SVG](#SVG) | Skalierbare Vektorgrafik-Datei (.svg) |
| [SVGZ](#SVGZ) | Komprimierte skalierbare Vektorgrafik-Datei (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Hypertext Markup Language File (.html) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. |
| [MHT](#MHT) | MHTML Web Archive (.mht) ist ein Webseiten-Archivformat, das von einer Reihe verschiedener Anwendungen erstellt werden kann. |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) ist ein Webseiten-Archivformat, das von einer Reihe verschiedener Anwendungen erstellt werden kann. |
| [ONE](#ONE) | OneNote-Dokumente (.one) werden von der Microsoft OneNote-Anwendung erstellt. |
| [PDF](#PDF) | Portable Document Format File (.pdf) ist ein Dateiformat, das als Standard für die Darstellung von Dokumenten und anderem Referenzmaterial eingeführt wurde und unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. |
| [XPS](#XPS) | XML Paper Specification File (.xps) stellt Seitenlayout-Dateien dar, die auf von Microsoft erstellten XML Paper Specifications basieren. |
| [TEX](#TEX) | LaTeX-Quelltext (.tex) ist eine Sprache, die Programmier- sowie Auszeichnungsfunktionen umfasst und zum Setzen von Dokumenten verwendet wird. |
| [PPT](#PPT) | PowerPoint-Präsentation (.ppt) stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) ist eine Präsentationsdatei, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurde. |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) ist eine mit Microsoft PowerPoint erstellte Datei für Diashowzwecke. |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) ist eine mit Microsoft PowerPoint 2007 und höher erstellte Datei für Diashowzwecke. |
| [ODP](#ODP) | OpenDocument Presentation (.odp) stellt das von OpenOffice.org im OASIS-Open-Standard verwendete Präsentationsdateiformat dar. |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) stellt Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden. |
| [XLS](#XLS) | Excel-Tabelle (.xls) ist eine Datei, die von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden kann. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) ist eine Art von Tabellenkalkulationsdateien, die Makros unterstützen. |
| [XLSB](#XLSB) | Excel Binary Spreadsheet (.xlsb) Dateiformat definiert das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen enthält, die den Inhalt einer Excel-Arbeitsmappe festlegen. |
| [CSV](#CSV) | Comma Separated Values File (.csv) stellt Klartextdateien dar, die Datensätze mit kommagetrennten Werten enthalten. |
| [TSV](#TSV) | Tab Separated Values File (.tsv) stellt Daten dar, die in Klartextformat durch Tabulatoren getrennt sind. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods). |
| [XLTM](#XLTM) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) stellt Dateien dar, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt werden. |
| [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) Dateien basieren auf den Spezifikationen des Office OpenXML-Dateiformats. |
| [XLT](#XLT) | Excel-Vorlagendatei (.xlt) sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. |
| [XLAM](#XLAM) | Excel-Makro‑aktiviertes Add-In (.xlam). |
| [DOC](#DOC) | Microsoft‑Word‑Dokument (.doc) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden. |
| [DOCX](#DOCX) | Microsoft‑Word‑Open‑XML‑Dokument (.docx) ist ein bekanntes Format für Microsoft‑Word‑Dokumente. |
| [DOCM](#DOCM) | Word‑Open‑XML‑Makro‑aktiviertes Dokument (.docm) Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. |
| [DOT](#DOT) | Word‑Dokumentvorlage (.dot) Dateien sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen. |
| [DOTX](#DOTX) | Word‑Open‑XML‑Dokumentvorlage (.dotx) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen. |
| [DOTM](#DOTM) | Word‑Open‑XML‑Makro‑aktivierte Dokumentvorlage (.dotm) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. |
| [RTF](#RTF) | Rich‑Text‑Format‑Datei (.rtf), eingeführt und dokumentiert von Microsoft, stellt das Rich‑Text‑Format (RTF) dar, ein Verfahren zur Kodierung von formatiertem Text und Grafiken zur Verwendung in Anwendungen. |
| [TXT](#TXT) | Plain‑Text‑Datei (.txt) stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält. |
| [ERR](#ERR) | Fehlerprotokoll‑Datei (.err) ist eine Textdatei, die Fehlermeldungen enthält, die von einem Programm erzeugt wurden. |
| [ODT](#ODT) | OpenDocument‑Text‑Dokument (.odt) Dateien sind Dokumente, die mit Textverarbeitungsanwendungen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren. |
| [OTT](#OTT) | OpenDocument‑Dokumentvorlage (.ott) stellt Vorlagendokumente dar, die von Anwendungen gemäß dem OpenDocument‑Standardformat der OASIS erzeugt werden. |
| [WAV](#WAV) | WAV, bekannt für WAVE (Waveform Audio File Format), ist ein Unterbereich des Resource Interchange File Format (RIFF) von Microsoft zur Speicherung digitaler Audiodateien. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Dateitypname z. B. |
| [getExtension()](#getExtension--) | Dateinamensuffix (einschließlich des Punktes ".") z. B. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Ordnet Dateierweiterungen Dateitypen zu. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Ruft unterstützte Dateitypen ab |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob der aktuelle [FileType](../../com.groupdocs.merger.domain/filetype) derselbe ist wie das angegebene [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekt. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob der aktuelle [FileType](../../com.groupdocs.merger.domain/filetype) derselbe ist wie das angegebene Objekt. |
| [hashCode()](#hashCode--) | Gibt den Hash‑Code für das aktuelle [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekt zurück. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob zwei [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekte identisch sind. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob zwei [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekte nicht identisch sind. |
| [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob der Eingabe‑[FileType](../../com.groupdocs.merger.domain/filetype) ein primitives Textformat ist. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob der Eingabe‑[FileType](../../com.groupdocs.merger.domain/filetype) ein Archivformat ist. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob der Eingabe‑[FileType](../../com.groupdocs.merger.domain/filetype) ein primitives Textformat ist. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Bestimmt, ob die Eingabe [FileType](../../com.groupdocs.merger.domain/filetype) ein Audioformat ist. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Stellt einen unbekannten Dateityp dar.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Gezippte Datei (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


7-Zip komprimierte Datei (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Konsolidiertes Unix-Dateiarchiv (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Roshal-Archiv komprimierte Datei (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Visio Stencil File (.vssx) sind Zeichenstencil, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind bekannt für die Darstellung einer Vielzahl von Zeichnungselementen wie Sammlungen von Formen, Verbindern, Flussdiagrammen, Netzwerklayouts, UML-Diagrammen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx) stellt das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) sind Zeichnungsdateien, die mit der Microsoft Visio-Anwendung erstellt wurden und Makros unterstützen. VSDM-Dateien sind OPC/XML-Zeichnungen, die VSDX ähneln, aber zudem die Möglichkeit bieten, Makros beim Öffnen der Datei auszuführen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) sind Zeichenvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX-Dateien bieten einen Ausgangspunkt für die Erstellung von Visio-Zeichnungen, die als .VSDX-Dateien gespeichert werden, mit Standardlayout und -einstellungen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX-Dateien können aus VSTM-Vorlagen erstellte Dateien Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) sind Microsoft Visio Stencil-Dateien, die Makros unterstützen. Wenn eine VSSM-Datei geöffnet wird, können die Makros ausgeführt werden, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) bezieht sich auf Stencils, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX-Dateien werden im XML-Dateiformat gespeichert und wurden bis Visio 2013 unterstützt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) ist eine Microsoft Visio-Zeichnungsvorlage, die auf der Festplatte im XML-Dateiformat gespeichert wird. Die Vorlage soll eine Datei mit Grundeinstellungen bereitstellen, die zur Erstellung mehrerer Visio-Dateien mit denselben Einstellungen verwendet werden kann. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx) ist eine in Microsoft Visio erstellte Zeichnung oder Grafik, die jedoch im XML-Format mit der Erweiterung .VDX gespeichert wird. Eine Visio-Zeichnungs‑XML‑Datei wird in der Visio‑Software erstellt, die von Microsoft entwickelt wurde. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) ist ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Verbraucher bereitstellt. Das Format ist inzwischen so verbreitet, dass es von vielen E‑Readern und Softwareanwendungen unterstützt wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap-Bilddatei (.bmp) stellt Dateien dar, die zum Speichern von Bitmap-Digitalbildern verwendet werden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG-Bild (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG-Bild (.jpeg) ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. Das Ergebnisbild ist als Folge der Kompression ein Kompromiss zwischen Speichergröße und Bildqualität. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) ist ein Rasterbilddateiformat, das verlustfreie Kompression verwendet. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript-Datei (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Getaggte Bilddatei (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Getaggtes Bilddateiformat (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Grafik-Austauschformat-Datei (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Skalierbare Vektorgrafik-Datei (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Komprimierte skalierbare Vektorgrafik-Datei (.svgz)

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


Hypertext Markup Language-Datei (.html) ist die Erweiterung für Webseiten, die zur Anzeige in Browsern erstellt werden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML-Webarchiv (.mht) ist ein Webseiten-Archivformat, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME-HTML-Datei (.mhtml) ist ein Webseiten-Archivformat, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


OneNote-Dokument (.one)-Dateien werden von der Microsoft OneNote-Anwendung erstellt. OneNote ermöglicht es Ihnen, Informationen zu sammeln, als würden Sie Ihr Notizblock zum Notieren verwenden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Portable Document Format-Datei (.pdf) ist ein Dateiformat, das als Standard zur Darstellung von Dokumenten und anderem Referenzmaterial eingeführt wurde, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


XML Paper Specification-Datei (.xps) stellt Seitenlayoutdateien dar, die auf von Microsoft erstellten XML Paper Specifications basieren. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


LaTeX-Quelldokument (.tex) ist eine Sprache, die Programmier- sowie Auszeichnungsfunktionen umfasst und zum Setzen von Dokumenten verwendet wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


PowerPoint-Präsentation (.ppt) stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie definiert das binäre Dateiformat, das von Microsoft PowerPoint 97-2003 verwendet wird. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


PowerPoint Open XML-Präsentation (.pptx) ist eine Präsentationsdatei, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurde. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX-Format auf dem Microsoft PowerPoint Open XML-Präsentationsdateiformat. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


PowerPoint-Diashow (.pps) ist eine Datei, die mit Microsoft PowerPoint für Diashow-Zwecke erstellt wurde. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


PowerPoint Open XML-Diashow (.ppsx) ist eine Datei, die mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


OpenDocument-Präsentation (.odp) stellt das von OpenOffice.org im OASISOpen-Standard verwendete Präsentationsdateiformat dar. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


OpenDocument Presentation Template (.otp) stellt Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt werden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Excel Spreadsheet (.xls) ist eine Datei, die von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Microsoft Excel Open XML Spreadsheet (.xlsx) ist ein bekanntes Format für Microsoft Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Excel Open XML Macro-Enabled Spreadsheet (.xlsm) ist eine Art von Tabellenkalkulationsdateien, die Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Das Dateiformat Excel Binary Spreadsheet (.xlsb) definiert das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen enthält, die den Inhalt von Excel‑Arbeitsmappen festlegen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Comma Separated Values File (.csv) stellt Klartextdateien dar, die Datensätze mit kommagetrennten Werten enthalten. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Tab Separated Values File (.tsv) stellt Daten dar, die im Klartextformat durch Tabulatoren getrennt sind. Erfahren Sie mehr über dieses Dateiformat [here][].


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


Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) stellt Dateien dar, die von Microsoft Excel als makrofähige Vorlagendateien erzeugt werden. XLTM‑Dateien ähneln XLTX in ihrer Struktur, außer dass letztere keine Vorlagendateien mit Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Excel Open XML Spreadsheet Template (.xltx)‑Dateien basieren auf den Spezifikationen des Office OpenXML‑Dateiformats. Sie werden verwendet, um eine Standardvorlagendatei zu erstellen, die zur Erzeugung von XLSX‑Dateien genutzt werden kann, die dieselben Einstellungen wie in der XLTX‑Datei aufweisen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt) sind Vorlagendateien, die mit Microsoft Excel erstellt werden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft‑Office‑Suite ist. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Excel-Makro‑aktiviertes Add-In (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärdateiformat erzeugt werden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) ist ein bekanntes Format für Microsoft Word‑Dokumente. Es wurde ab 2007 mit der Veröffentlichung von Microsoft Office 2007 eingeführt; die Struktur dieses neuen Dokumentformats wurde von reinem Binärformat zu einer Kombination aus XML‑ und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm)‑Dateien sind von Microsoft Word 2007 oder höher erzeugte Dokumente mit der Möglichkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word-Dokumentvorlagen (.dot) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOC- oder DOCX-Dateien zu haben. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Dokumentvorlagen (.dotx) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Erstellung weiterer DOCX-Dateien zu haben. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Makro‑aktivierte Dokumentvorlage (.dotm) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich‑Text‑Format‑Datei (.rtf), eingeführt und dokumentiert von Microsoft, stellt das Rich Text Format (RTF) eine Methode dar, formatierte Texte und Grafiken für die Verwendung in Anwendungen zu codieren. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain‑Text‑Datei (.txt) stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Fehlerprotokolldatei (.err) ist eine Textdatei, die Fehlermeldungen enthält, die von einem Programm erzeugt wurden. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument‑Textdokumente (.odt) sind Dokumente, die mit Textverarbeitungsprogrammen erstellt werden, die auf dem OpenDocument‑Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument‑Dokumentvorlagen (.ott) stellen Vorlagendokumente dar, die von Anwendungen erzeugt werden und dem OpenDocument‑Standardformat der OASIS entsprechen. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, bekannt für WAVE (Waveform Audio File Format), ist ein Teil der Resource Interchange File Format (RIFF)-Spezifikation von Microsoft zum Speichern digitaler Audiodateien. Das Format wendet keine Kompression auf den Bitstrom an und speichert die Audioaufnahmen mit unterschiedlichen Abtastraten und Bitraten. Es war und ist eines der Standardformate für Audio‑CDs. Erfahren Sie mehr über dieses Dateiformat [here][].


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Dateitypname, z. B. \"Microsoft Word Document\".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Dateinamen‑Suffix (einschließlich des Punktes \".\"), z. B. \".doc\".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Ordnet Dateierweiterungen Dateitypen zu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Erweiterung | java.lang.String | Dateierweiterung (einschließlich des Punktes \".\"). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ruft unterstützte Dateitypen ab

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> – Gibt die Sequenz unterstützter Dateitypen zurück
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Bestimmt, ob der aktuelle [FileType](../../com.groupdocs.merger.domain/filetype) derselbe ist wie das angegebene [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | Das Objekt, das mit dem aktuellen [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt verglichen werden soll. |

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

wenn

```
obj
```

Parameter ist [FileType](../../com.groupdocs.merger.domain/filetype) und ist dasselbe wie das aktuelle [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt; andernfalls,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hash‑Code für das aktuelle [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekt zurück.

**Returns:**
int – Ein Hash‑Code für das aktuelle [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Bestimmt, ob zwei [FileType](../../com.groupdocs.merger.domain/filetype)‑Objekte identisch sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Linkes [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Rechtes [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt. |

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

wenn beide [FileType](../../com.groupdocs.merger.domain/filetype)-Objekte nicht identisch sind; andernfalls,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.

**Returns:**
java.lang.String - Eine Zeichenkette, die das aktuelle Objekt darstellt.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Bestimmt, ob der Eingabe‑[FileType](../../com.groupdocs.merger.domain/filetype) ein primitives Textformat ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Das [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt. |

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

wenn das Eingabe-[FileType](../../com.groupdocs.merger.domain/filetype) ein Archivformat ist; andernfalls,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Bestimmt, ob der Eingabe‑[FileType](../../com.groupdocs.merger.domain/filetype) ein primitives Textformat ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Das [FileType](../../com.groupdocs.merger.domain/filetype)-Objekt. |

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

wenn das Eingabe-[FileType](../../com.groupdocs.merger.domain/filetype) ein Audioformat ist; andernfalls,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
