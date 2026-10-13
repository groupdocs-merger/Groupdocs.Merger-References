---
title: "FileType"
second_title: "Riferimento API di GroupDocs.Merger per .NET"
description: "Rappresenta il tipo di file. Fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da GroupDocs.Merger, rilevare il tipo di file per estensione, ecc."
type: docs
weight: 110
url: /it/net/groupdocs.merger.domain/filetype/
---
## FileType class

Rappresenta il tipo di file. Fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da **GroupDocs.Merger**, rilevare il tipo di file per estensione, ecc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Suffisso del nome file (incluso il punto ".") ad es. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nome del tipo di file, ad es. "Microsoft Word Document". |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Mappa l'estensione del file al tipo di file. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Determina se il corrente [`FileType`](../filetype) è lo stesso dell'oggetto [`FileType`](../filetype) specificato. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Determina se il corrente [`FileType`](../filetype) è lo stesso dell'oggetto specificato. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Restituisce il codice hash per l'oggetto [`FileType`](../filetype) corrente. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Recupera i tipi di file supportati |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Determina se il [`FileType`](../filetype) di input è un formato archivio. |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | Determina se il [`FileType`](../filetype) di input è un formato audio. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Determina se il [`FileType`](../filetype) di input è un formato immagine. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Determina se il [`FileType`](../filetype) di input è un formato di testo primitivo. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Determina se due oggetti [`FileType`](../filetype) sono gli stessi. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Determina se due oggetti [`FileType`](../filetype) non sono gli stessi. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | Il file immagine bitmap (.bmp) rappresenta i file che vengono usati per memorizzare immagini digitali bitmap. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | File compresso Bzip2 (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | Il file valori separati da virgola (.csv) rappresenta file di testo semplice che contengono record di dati con valori separati da virgola. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/csv). |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Il documento Microsoft Word (.doc) rappresenta documenti generati da Microsoft Word o da altri programmi di elaborazione testi in formato file binario. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | I file Word Open XML Macro-Enabled Document (.docm) sono documenti generati da Microsoft Word 2007 o versioni successive con la capacità di eseguire macro. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) è un formato molto noto per i documenti Microsoft Word. Introdotto dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da puro binario a una combinazione di file XML e binari. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | I file Word Document Template (.dot) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | I file Word Open XML Document Template (.dotx) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows Enhanced Metafile (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows Compressed Enhanced Metafile (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è ormai così comune che è supportato da molti e-reader e applicazioni software. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/ebook/epub). |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log File (.err) è un file di testo che contiene messaggi di errore generati da un programma. Scopri di più su questo formato di file [qui](https://fileinfo.com/extension/err). |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | File Graphical Interchange Format (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | File compresso G-Zip (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) è l'estensione per le pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/web/html). |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG Image (.jpeg) è un tipo di formato immagine salvato usando il metodo di compressione con perdita. L'immagine risultante, come risultato della compressione, è un compromesso tra dimensione di archiviazione e qualità dell'immagine. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG Image (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) è un formato di archivio di pagine web che può essere creato da diverse applicazioni. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/web/mhtml). |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) è un formato di archivio di pagine web che può essere creato da diverse applicazioni. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/web/mhtml). |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | I file con estensione .mp3 sono formati di file audio digitalmente codificati, basati formalmente su MPEG-1 Audio Layer III o MPEG-2 Audio Layer III. Sono stati sviluppati dal Moving Picture Experts Group (MPEG) che utilizza la compressione audio Layer 3. La compressione ottenuta dal formato MP3 è 1/10 della dimensione dei file .WAV o .AIF. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/audio/mp3). |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) rappresenta il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | I file OpenDocument Text Document (.odt) sono un tipo di documento creato con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/odt). |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | I file OneNote Document (.one) sono creati dall'applicazione Microsoft OneNote. OneNote ti consente di raccogliere informazioni usando l'applicazione come se stessi usando il tuo blocco note per prendere appunti. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/note-taking/one). |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | Il modello di presentazione OpenDocument Presentation Template (.otp) rappresenta file modello di presentazione creati da applicazioni nel formato standard OASIS OpenDocument. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/presentation/otp). |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | Il modello di documento OpenDocument Document Template (.ott) rappresenta documenti modello generati da applicazioni in conformità con lo standard OpenDocument di OASIS. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/ott). |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | Il file Portable Document Format (.pdf) è un formato di file introdotto come standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/view/pdf). |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Il Portable Network Graphic (.png) è un tipo di formato di immagine raster che utilizza compressione senza perdita. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/png). |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) è un file creato con Microsoft PowerPoint per scopi di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) è un file creato con Microsoft PowerPoint 2007 e versioni successive per scopi di presentazione. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) rappresenta un file PowerPoint che consiste in una raccolta di diapositive per la visualizzazione come presentazione. Specifica il Binary File Format utilizzato da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) è un file di presentazione creato con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT, che era binario, il formato PPTX si basa sul formato di presentazione Open XML di Microsoft PowerPoint. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript File (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive Compressed File (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/rtf). |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip Compressed File (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Scalable Vector Graphics File (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Scalable Vector Graphics Compressed File (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | Consolidated Unix File Archive (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Source Document (.tex) è un linguaggio che comprende funzionalità di programmazione e di markup, usato per impaginare documenti. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/page-description-language/tex). |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | Tagged Image File (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Tagged Image File Format (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tab Separated Values File (.tsv) rappresenta dati separati da tabulazioni in formato di testo semplice. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) rappresenta un documento di testo che contiene testo semplice sotto forma di righe. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Rappresenta un tipo di file sconosciuto. |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Il file Visio Drawing XML (.vdx) è un disegno o diagramma creato in Microsoft Visio, ma salvato in formato XML con estensione .VDX. Un file Visio Drawing XML viene creato nel software Visio, sviluppato da Microsoft. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | File di disegno Visio (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | I Visio Macro-Enabled Drawing (.vsdm) sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma offrono anche la possibilità di eseguire macro quando il file viene aperto. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Il Visio Drawing (.vsdx) rappresenta il formato file Microsoft Visio introdotto a partire da Microsoft Office 2013. È stato sviluppato per sostituire il formato file binario .VSD, supportato dalle versioni precedenti di Microsoft Visio. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | File stencil Visio(.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Il Visio Macro-Enabled Stencil File (.vssm) sono file stencil Microsoft Visio che forniscono supporto per le macro. Un file VSSM, quando aperto, consente di eseguire le macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Il Visio Stencil File (.vssx) sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. Il formato file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per la rappresentazione di una varietà di elementi di disegno, come collezioni di forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Modello di disegno Visio (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Il Visio Macro-Enabled Drawing Template (.vstm) sono file modello creati con Microsoft Visio che supportano le macro. A differenza dei file VSDX, i file creati da modelli VSTM possono eseguire macro sviluppate in codice Visual Basic for Applications (VBA). Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Il Visio Drawing Template (.vstx) sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono un punto di partenza per creare disegni Visio, salvati come file .VSDX, con layout e impostazioni predefinite. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Il Visio Stencil XML File (.vsx) si riferisce a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX sono salvati in formato XML e sono stati supportati fino a Visio 2013. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Il Visio Template XML File (.vtx) è un modello di disegno Microsoft Visio salvato su disco in formato XML. Il modello è pensato per fornire un file con impostazioni di base che può essere usato per creare più file Visio con le stesse impostazioni. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV, noto per WAVE (Waveform Audio File Format), è un sottoinsieme della specifica Resource Interchange File Format (RIFF) di Microsoft per la memorizzazione di file audio digitali. Il formato non applica alcuna compressione al flusso di bit e memorizza le registrazioni audio con diverse frequenze di campionamento e bitrate. È stato e rimane uno dei formati standard per i CD audio. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Componenti aggiuntivi Excel Macro-Enabled (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Il foglio di calcolo Excel (.xls) è un file che può essere creato da Microsoft Excel così come da altri programmi di fogli di calcolo simili, come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Il formato file Excel Binary Spreadsheet (.xlsb) specifica l'Excel Binary File Format, che è una collezione di record e strutture che definiscono il contenuto di una cartella di lavoro Excel. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) è un tipo di file di foglio di calcolo che supporta le macro. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) è un formato noto per i documenti Microsoft Excel, introdotto da Microsoft con il rilascio di Microsoft Office 2007. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) sono file modello creati con Microsoft Excel, un'applicazione di foglio di calcolo che fa parte della suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT così come l'apertura di questi. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) rappresenta i file generati da Microsoft Excel come modelli abilitati alle macro. I file XLTM sono simili a XLTX nella struttura, tranne per il fatto che quest'ultimo non supporta la creazione di modelli con macro. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | I file Excel Open XML Spreadsheet Template (.xltx) si basano sulle specifiche del formato di file Office OpenXML. Vengono utilizzati per creare un file modello standard che può essere impiegato per generare file XLSX con le stesse impostazioni specificate nel file XLTX. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/spreadsheet/xltx). |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) rappresenta file di layout di pagina basati sulle XML Paper Specifications create da Microsoft. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/page-description-language/xps). |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | File compresso (.zip) |

### Osservazioni

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Vedi anche

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
