---
title: "FileType"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Stellt den Dateityp dar. Bietet Methoden, um eine Liste aller von GroupDocs.Merger unterstützten Dateitypen zu erhalten, den Dateityp anhand der Erweiterung zu erkennen usw."
type: docs
weight: 110
url: /de/net/groupdocs.merger.domain/filetype/
---
## FileType class

Stellt einen Dateityp dar. Bietet Methoden, um eine Liste aller von **GroupDocs.Merger** unterstützten Dateitypen zu erhalten, den Dateityp anhand der Erweiterung zu erkennen usw.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Dateitypname, z. B. "Microsoft Word Document". |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Ordnet Dateierweiterungen Dateitypen zu. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Bestimmt, ob der aktuelle [`FileType`](../filetype) derselbe ist wie das angegebene [`FileType`](../filetype)-Objekt. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Bestimmt, ob der aktuelle [`FileType`](../filetype) derselbe ist wie das angegebene Objekt. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Gibt den Hashcode für das aktuelle [`FileType`](../filetype)-Objekt zurück. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Ruft unterstützte Dateitypen ab |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Bestimmt, ob der Eingabe-[`FileType`](../filetype) ein Archivformat ist. |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | Bestimmt, ob der Eingabe-[`FileType`](../filetype) ein Audioformat ist. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Bestimmt, ob der Eingabe-[`FileType`](../filetype) ein Bildformat ist. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Bestimmt, ob der Eingabe-[`FileType`](../filetype) ein primitives Textformat ist. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Bestimmt, ob zwei [`FileType`](../filetype)-Objekte identisch sind. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Bestimmt, ob zwei [`FileType`](../filetype)-Objekte nicht identisch sind. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap-Bilddatei (.bmp) stellt Dateien dar, die zur Speicherung von Bitmap-Digitalbildern verwendet werden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2-komprimierte Datei (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | Kommagetrennte Werte-Datei (.csv) stellt Textdateien dar, die Datensätze mit kommagetrennten Werten enthalten. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/spreadsheet/csv). |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word-Dokument (.doc) stellt Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsprogrammen im Binärformat erzeugt werden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm)-Dateien sind von Microsoft Word 2007 oder höher erstellte Dokumente mit der Möglichkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) ist ein bekanntes Format für Microsoft Word‑Dokumente. Eingeführt ab 2007 mit der Veröffentlichung von Microsoft Office 2007, wurde die Struktur dieses neuen Dokumentformats von rein binär zu einer Kombination aus XML‑ und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | Word Document Template (.dot)-Dateien sind Vorlagendateien, die von Microsoft Word erstellt werden, um vordefinierte Einstellungen für die Erstellung weiterer DOC‑ oder DOCX‑Dateien zu besitzen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) sind Vorlagendateien, die von Microsoft Word erstellt werden, um vordefinierte Einstellungen für die Erstellung weiterer DOCX‑Dateien zu besitzen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows Enhanced Metafile (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows Compressed Enhanced Metafile (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) ist ein eBook-Dateiformat, das ein standardisiertes digitales Publikationsformat für Verlage und Leser bereitstellt. Das Format ist inzwischen so verbreitet, dass es von vielen E‑Readern und Softwareanwendungen unterstützt wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/ebook/epub). |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log File (.err) ist eine Textdatei, die Fehlermeldungen enthält, die von einem Programm erzeugt wurden. Erfahren Sie mehr über dieses Dateiformat [hier](https://fileinfo.com/extension/err). |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | Graphical Interchange Format File (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip Compressed File (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) ist die Dateierweiterung für Webseiten, die zur Anzeige in Browsern erstellt wurden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/web/html). |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG Image (.jpeg) ist ein Bildformat, das mit verlustbehafteter Kompression gespeichert wird. Das resultierende Bild stellt einen Kompromiss zwischen Dateigröße und Bildqualität dar. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG Image (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) ist ein Webseitensicherungsformat, das von verschiedenen Anwendungen erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/web/mhtml). |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) ist ein Webseitensicherungsformat, das von verschiedenen Anwendungen erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/web/mhtml). |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | Dateien mit der Erweiterung .mp3 sind digital codierte Dateiformate für Audiodateien, die formal auf MPEG-1 Audio Layer III oder MPEG-2 Audio Layer III basieren. Sie wurden von der Moving Picture Experts Group (MPEG) entwickelt, die die Layer‑3‑Audiokompression verwendet. Die durch das MP3‑Dateiformat erreichte Kompression beträgt ein Zehntel der Größe von .WAV‑ oder .AIF‑Dateien. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/audio/mp3). |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) ist ein Präsentationsdateiformat, das von OpenOffice.org im OASIS‑Open‑Standard verwendet wird. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods). Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument Text Document (.odt)-Dateien sind Dokumente, die mit Textverarbeitungsprogrammen erstellt werden und auf dem OpenDocument‑Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/odt). |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote Document (.one)-Dateien werden von der Microsoft‑OneNote‑Anwendung erstellt. OneNote ermöglicht es Ihnen, Informationen zu sammeln, als würden Sie Ihr Notizblock zum Schreiben von Notizen verwenden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/note-taking/one). |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument Presentation Template (.otp) steht für Präsentationsvorlagendateien, die von Anwendungen im OASIS‑OpenDocument‑Standardformat erstellt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/presentation/otp). |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Document Template (.ott) steht für Vorlagendokumente, die von Anwendungen in Übereinstimmung mit dem OpenDocument‑Standardformat von OASIS erzeugt werden. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/word-processing/ott). |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) ist ein Dateiformat, das als Standard zur Darstellung von Dokumenten und anderem Referenzmaterial in einem Format eingeführt wurde, das unabhängig von Anwendungssoftware, Hardware sowie Betriebssystem ist. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/view/pdf). |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) ist ein Rasterbilddateiformat, das verlustfreie Kompression verwendet. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/image/png). |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) ist eine Datei, die mit Microsoft PowerPoint für Präsentationszwecke erstellt wurde. Das Lesen und Erstellen von PPS‑Dateien wird von Microsoft PowerPoint 97‑2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) ist eine Datei, die mit Microsoft PowerPoint 2007 und höher für Präsentationszwecke erstellt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint-Präsentation (.ppt) stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien für die Anzeige als Diashow besteht. Sie gibt das binäre Dateiformat an, das von Microsoft PowerPoint 97-2003 verwendet wird. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML Makroaktivierte Präsentation |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Präsentation (.pptx) ist eine Präsentationsdatei, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurde. Im Gegensatz zur vorherigen Version des Präsentationsdateiformats PPT, das binär war, basiert das PPTX-Format auf dem Microsoft PowerPoint Open XML Präsentationsdateiformat. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript-Datei (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive komprimierte Datei (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format Datei (.rtf) wurde von Microsoft eingeführt und dokumentiert; das Rich Text Format (RTF) stellt eine Methode zur Codierung von formatiertem Text und Grafiken für die Verwendung in Anwendungen dar. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/word-processing/rtf). |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip komprimierte Datei (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Scalable Vector Graphics-Datei (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Scalable Vector Graphics komprimierte Datei (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | Konsolidiertes Unix-Archiv (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX-Quelltextdokument (.tex) ist eine Sprache, die Programmierung sowie Auszeichnungsfunktionen umfasst und zum Satz von Dokumenten verwendet wird. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/page-description-language/tex). |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | Tagged Image File (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Tagged Image File Format (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tabulatorgetrennte Werte-Datei (.tsv) stellt Daten dar, die in einem Klartextformat durch Tabs getrennt sind. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Klartextdatei (.txt) stellt ein Textdokument dar, das reinen Text in Form von Zeilen enthält. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Stellt einen unbekannten Dateityp dar. |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) ist eine Zeichnung oder ein Diagramm, das in Microsoft Visio erstellt, aber im XML-Format mit der Erweiterung .VDX gespeichert wurde. Eine Visio Drawing XML-Datei wird in der Visio-Software erstellt, die von Microsoft entwickelt wurde. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | Visio-Zeichnungsdatei (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio-Makroaktivierte Zeichnung (.vsdm) sind Zeichnungsdateien, die mit der Microsoft Visio-Anwendung erstellt wurden und Makros unterstützen. VSDM-Dateien sind OPC/XML-Zeichnungen, die VSDX ähneln, aber zudem die Möglichkeit bieten, Makros beim Öffnen der Datei auszuführen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) stellt das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | Visio-Stencil-Datei (.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio-Makro‑aktivierte Stencil‑Datei (.vssm) sind Microsoft Visio Stencil‑Dateien, die Unterstützung für Makros bieten. Eine VSSM‑Datei lässt beim Öffnen die Ausführung von Makros zu, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil‑Datei (.vssx) sind Zeichen‑Stencils, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX‑Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio‑Dateien sind bekannt für die Darstellung einer Vielzahl von Zeichnungselementen wie Sammlungen von Formen, Verbindern, Flussdiagrammen, Netzwerk‑Layouts, UML‑Diagrammen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Visio‑Zeichnungsvorlage (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio‑Makro‑aktivierte Zeichnungsvorlage (.vstm) sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX‑Dateien können aus VSTM‑Vorlagen erstellte Dateien Makros ausführen, die in Visual Basic for Applications (VBA)-Code entwickelt wurden. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio‑Zeichnungsvorlage (.vstx) sind Zeichnungsvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX‑Dateien bieten einen Ausgangspunkt für die Erstellung von Visio‑Zeichnungen, die als .VSDX‑Dateien gespeichert werden, mit Standardlayout und -einstellungen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil‑XML‑Datei (.vsx) bezeichnet Stencils, die aus Zeichnungen und Formen bestehen und zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX‑Dateien werden im XML‑Dateiformat gespeichert und wurden bis Visio 2013 unterstützt. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio‑Vorlagen‑XML‑Datei (.vtx) ist eine Microsoft Visio Zeichnungsvorlage, die auf der Festplatte im XML‑Dateiformat gespeichert wird. Die Vorlage soll eine Datei mit Grundeinstellungen bereitstellen, die zur Erstellung mehrerer Visio‑Dateien mit denselben Einstellungen verwendet werden kann. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV, bekannt für WAVE (Waveform Audio File Format), ist ein Teil der Resource Interchange File Format (RIFF)-Spezifikation von Microsoft zur Speicherung digitaler Audiodateien. Das Format wendet keine Kompression auf den Bitstrom an und speichert Audioaufnahmen mit unterschiedlichen Abtastraten und Bitraten. Es war und ist eines der Standardformate für Audio‑CDs. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel‑Makro‑aktiviertes Add‑In (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel‑Tabellendokument (.xls) ist eine Datei, die von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden kann. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel‑Binary‑Tabellendokument (.xlsb) bezeichnet das Excel Binary File Format, das eine Sammlung von Datensätzen und Strukturen ist, die den Inhalt einer Excel‑Arbeitsmappe festlegen. Weitere Informationen zu diesem Dateiformat finden Sie [hier](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) ist ein Typ von Tabellenkalkulationsdateien, die Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) ist ein bekanntes Format für Microsoft Excel‑Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office‑Suite ist. Microsoft Office 97‑2003 unterstützte das Erstellen neuer XLT‑Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) stellt Dateien dar, die von Microsoft Excel als makroaktivierte Vorlagendateien erzeugt werden. XLTM‑Dateien ähneln XLTX in ihrer Struktur, außer dass Letztere keine Vorlagendateien mit Makros unterstützen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) Dateien basieren auf den Office OpenXML‑Dateiformatspezifikationen. Sie werden verwendet, um eine Standardvorlagendatei zu erstellen, die zur Erzeugung von XLSX‑Dateien genutzt werden kann, die dieselben Einstellungen wie in der XLTX‑Datei aufweisen. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/xltx). |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) stellt Seitenlayout‑Dateien dar, die auf von Microsoft erstellten XML Paper Specifications basieren. Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/page-description-language/xps). |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | ZIP‑Datei (.zip) |

### Bemerkungen

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Siehe auch

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
