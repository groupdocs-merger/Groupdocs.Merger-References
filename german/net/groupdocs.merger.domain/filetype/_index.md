---
title: FileType
second_title: GroupDocs.Merger für .NET-API-Referenz
description: Repräsentiert den Dateityp. Stellt Methoden bereit um eine Liste aller unterstützten Dateitypen zu erhaltenGroupDocs.Merger  erkennt Dateityp nach Erweiterung etc.
type: docs
weight: 100
url: /de/net/groupdocs.merger.domain/filetype/
---
## FileType class

Repräsentiert den Dateityp. Stellt Methoden bereit, um eine Liste aller unterstützten Dateitypen zu erhalten**GroupDocs.Merger** , erkennt Dateityp nach Erweiterung etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Dateinamensuffix (einschließlich Punkt „.“) zB „.doc“. |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Name des Dateityps, z. B. "Microsoft Word-Dokument". |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Ordnet die Dateierweiterung dem Dateityp zu. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Bestimmt, ob der Strom[`FileType`](../filetype) ist genauso wie angegeben[`FileType`](../filetype) Objekt. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Bestimmt, ob der Strom[`FileType`](../filetype) ist das gleiche wie das angegebene Objekt. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Gibt den Hash-Code für den Strom zurück[`FileType`](../filetype) Objekt. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Ruft unterstützte Dateitypen ab |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Bestimmt, ob Eingang[`FileType`](../filetype) ist Archivformat. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Bestimmt, ob Eingang[`FileType`](../filetype) ist Bildformat. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Bestimmt, ob Eingang[`FileType`](../filetype) ist ein primitives Textformat. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Bestimmt, ob zwei[`FileType`](../filetype) Objekte sind gleich. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Bestimmt, ob zwei[`FileType`](../filetype) Objekte sind nicht gleich. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap-Bilddateien (.bmp) stellen Dateien dar, die zum Speichern digitaler Bitmap-Bilder verwendet werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Bzip2 komprimierte Datei (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Comma Separated Values File (.csv) stellt reine Textdateien dar, die Datensätze mit kommagetrennten Werten enthalten. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word-Dokumente (.doc) stellen Dokumente dar, die von Microsoft Word oder anderen Textverarbeitungsdokumenten im binären Dateiformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Word Open XML Macro-Enabled Document (.docm)-Dateien sind Microsoft Word 2007 oder höher erstellte Dokumente mit der Fähigkeit, Makros auszuführen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) ist ein bekanntes Format für Microsoft Word-Dokumente. Die Struktur dieses neuen Dokumentformats, das 2007 mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde, wurde von einer reinen Binärdatei in eine Kombination aus XML- und Binärdateien geändert. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Word-Dokumentvorlagendateien (.dot) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Generierung weiterer DOC- oder DOCX-Dateien zu haben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) stellt eine Vorlagendatei dar, die mit Microsoft Word 2007 oder höher erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) sind Vorlagendateien, die von Microsoft Word erstellt wurden, um vorformatierte Einstellungen für die Generierung weiterer DOCX-Dateien zu haben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) ist ein E-Book-Dateiformat, das ein digitales Standardveröffentlichungsformat für Verlage und Verbraucher bietet. Das Format ist inzwischen so weit verbreitet, dass es von vielen E-Readern und Softwareanwendungen unterstützt wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Fehlerprotokolldatei (.err) ist eine Textdatei, die von einem Programm generierte Fehlermeldungen enthält. Erfahren Sie mehr über dieses Dateiformat[Hier](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | Graphical Interchange Format-Datei (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip-komprimierte Datei (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) ist die Erweiterung für Webseiten, die für die Anzeige in Browsern erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG-Bild (.jpeg) ist ein Bildformat, das mit der Methode der verlustbehafteten Komprimierung gespeichert wird. Das Ausgabebild ist als Ergebnis der Komprimierung ein Kompromiss zwischen Speichergröße und Bildqualität. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG-Bild (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML-Webarchiv (.mht) ist ein Archivformat für Webseiten, das von einer Reihe unterschiedlicher Anwendungen erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME-HTML-Datei (.mhtml) ist ein Archivformat für Webseiten, das von einer Reihe verschiedener Anwendungen erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument-Präsentation (.odp) stellt das Präsentationsdateiformat dar, das von OpenOffice.org im OASISOpen-Standard verwendet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | OpenDocument-Textdokumentdateien (.odt) sind Dokumenttypen, die mit Textverarbeitungsanwendungen erstellt wurden, die auf dem OpenDocument-Textdateiformat basieren. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | OneNote-Dokumentdateien (.one) werden von der Microsoft OneNote-Anwendung erstellt. Mit OneNote können Sie mithilfe der Anwendung Informationen sammeln, als ob Sie Ihren Zeichenblock zum Aufzeichnen von Notizen verwenden würden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument-Präsentationsvorlage (.otp) stellt Präsentationsvorlagendateien dar, die von Anwendungen im OASIS OpenDocument-Standardformat erstellt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Document Template (.ott) stellen Vorlagendokumente dar, die von Anwendungen in Übereinstimmung mit dem OpenDocument-Standardformat von OASIS generiert wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) ist ein Dateiformat, das als Standard für die Darstellung von Dokumenten und anderem Referenzmaterial in einem Format eingeführt werden sollte, das unabhängig von Anwendungssoftware, Hardware und Betriebssystem ist. Erfahren Sie mehr über diese Datei Format[Hier](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) ist ein Rasterbild-Dateiformat, das verlustfreie Komprimierung verwendet. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint-Diashow (.pps) ist eine Datei, die mit Microsoft PowerPoint für Diashowzwecke erstellt wurde. Das Lesen und Erstellen von PPS-Dateien wird von Microsoft PowerPoint 97-2003 unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) ist eine Datei, die mit Microsoft PowerPoint 2007 und höher für Diashow-Zwecke erstellt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint-Präsentation (.ppt) stellt eine PowerPoint-Datei dar, die aus einer Sammlung von Folien zur Anzeige als Diashow besteht. Es gibt das von Microsoft PowerPoint 97-2003 verwendete binäre Dateiformat an. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML-Präsentation (.pptx) ist eine Präsentationsdatei, die mit der beliebten Microsoft PowerPoint-Anwendung erstellt wurde. Anders als die vorherige Version des Präsentationsdateiformats PPT, die binär war, basiert das PPTX-Format auf dem offenen XML-Präsentationsdateiformat von Microsoft PowerPoint. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript-Datei (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive komprimierte Datei (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich-Text-Format-Datei (.rtf) Das von Microsoft eingeführte und dokumentierte Rich-Text-Format (RTF) stellt eine Methode zum Codieren von formatiertem Text und Grafiken zur Verwendung in Anwendungen dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip-komprimierte Datei (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Konsolidiertes Unix-Dateiarchiv (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX-Quelldokument (.tex) ist eine Sprache, die sowohl Programmier- als auch Markup-Funktionen umfasst, die zum Setzen von Dokumenten verwendet werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | Markierte Bilddatei (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Markiertes Bilddateiformat (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tabulatorgetrennte Wertedatei (.tsv) stellt durch Tabulatoren getrennte Daten im Nur-Text-Format dar. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) stellt ein Textdokument dar, das einfachen Text in Form von Zeilen enthält. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | steht für unbekannten Dateityp. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio-Zeichnungs-XML-Datei (.vdx) ist eine Zeichnung oder ein Diagramm, das in Microsoft Visio erstellt, aber im XML-Format gespeichert wird und die Erweiterung .VDX hat. Eine Visio-Zeichnungs-XML-Datei wird in der von Microsoft entwickelten Visio-Software erstellt. Weitere Informationen zu diesem Dateiformat[Hier](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) sind Zeichnungsdateien, die mit der Microsoft Visio-Anwendung erstellt wurden, die Makros unterstützt. VSDM-Dateien sind OPC/XML-Zeichnungen, die VSDX ähneln, aber auch die Möglichkeit bieten, Makros auszuführen, wenn die Datei geöffnet wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio-Zeichnung (.vsdx) stellt das Microsoft Visio-Dateiformat dar, das ab Microsoft Office 2013 eingeführt wurde. Es wurde entwickelt, um das binäre Dateiformat .VSD zu ersetzen, das von früheren Versionen von Microsoft Visio unterstützt wird. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) sind Microsoft Visio-Schablonendateien, die Makros unterstützen. Wenn eine VSSM-Datei geöffnet wird, können Makros ausgeführt werden, um die gewünschte Formatierung und Platzierung von Formen in einem Diagramm zu erreichen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio-Schablonendatei (.vssx) sind Zeichnungsschablonen, die mit Microsoft Visio 2013 und höher erstellt wurden. Das VSSX-Dateiformat kann mit Visio 2013 und höher geöffnet werden. Visio-Dateien sind für die Darstellung einer Vielzahl von Zeichnungselementen bekannt, z. B. Sammlung von Formen, Konnektoren, Flussdiagramme, Netzwerklayout, UML-Diagramme, . Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) sind Vorlagendateien, die mit Microsoft Visio erstellt wurden und Makros unterstützen. Im Gegensatz zu VSDX-Dateien können aus VSTM-Vorlagen erstellte Dateien Makros ausführen, die in VBA-Code (Visual Basic for Applications) entwickelt wurden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio-Zeichnungsvorlage (.vstx) sind Zeichnungsvorlagendateien, die mit Microsoft Visio 2013 und höher erstellt wurden. Diese VSTX-Dateien bieten einen Ausgangspunkt zum Erstellen von Visio-Zeichnungen, die als VSDX-Dateien mit Standardlayout und Standardeinstellungen gespeichert werden. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio-Schablonen-XML-Datei (.vsx) bezieht sich auf Schablonen, die aus Zeichnungen und Formen bestehen, die zum Erstellen von Diagrammen in Microsoft Visio verwendet werden. VSX-Dateien werden im XML-Dateiformat gespeichert und wurden bis Visio 2013 unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio-Vorlagen-XML-Datei (.vtx) ist eine Microsoft Visio-Zeichnungsvorlage, die im XML-Dateiformat auf Datenträger gespeichert wird. Die Vorlage soll eine Datei mit Grundeinstellungen bereitstellen, die zum Erstellen mehrerer Visio-Dateien mit denselben Einstellungen verwendet werden kann. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Makrofähiges Excel-Add-In (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) ist eine Datei, die von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden kann. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel-Binärtabellendateiformat (.xlsb) gibt das Excel-Binärdateiformat an, bei dem es sich um eine Sammlung von Datensätzen und Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) ist eine Art Tabellenkalkulationsdatei, die Makros unterstützt. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) ist ein bekanntes Format für Microsoft Excel-Dokumente, das von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurde. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel-Vorlagendatei (.xlt) sind Vorlagendateien, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office-Suite ist. Microsoft Office 97-2003 unterstützte das Erstellen neuer XLT-Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) stellt Dateien dar, die von Microsoft Excel als Makro-aktivierte Vorlagendateien generiert werden. XLTM-Dateien ähneln XLTX in ihrer Struktur, abgesehen davon, dass letztere das Erstellen von Vorlagendateien mit Makros nicht unterstützen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML-Tabellenvorlagendateien (.xltx) basieren auf den Office OpenXML-Dateiformatspezifikationen. Es wird verwendet, um eine Standardvorlagendatei zu erstellen, die zum Generieren von XLSX-Dateien verwendet werden kann, die dieselben Einstellungen wie in der XLTX-Datei angegeben aufweisen. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML-Papierspezifikationsdatei (.xps) stellt Seitenlayoutdateien dar, die auf von Microsoft erstellten XML-Papierspezifikationen basieren. Erfahren Sie mehr über dieses Dateiformat[Hier](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | ZIP-Datei (.zip) |

### Bemerkungen

**Erfahren Sie mehr**

* Erfahren Sie mehr über die von GroupDocs.Merger unterstützten Dateiformate: [Vollständige Liste der unterstützten Dokumentformate](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Weitere Informationen zum Abrufen unterstützter Dateitypen im Code: [So erhalten Sie unterstützte Dateiformate im Code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Siehe auch

* namensraum [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* Montage [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
