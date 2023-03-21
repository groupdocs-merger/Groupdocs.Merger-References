---
title: FileType
second_title: Riferimento API GroupDocs.Merger per .NET
description: Rappresenta il tipo di file. Fornisce metodi per ottenere lelenco di tutti i tipi di file supportati daGroupDocs.Merger  rileva il tipo di file per estensione ecc.
type: docs
weight: 100
url: /it/net/groupdocs.merger.domain/filetype/
---
## FileType class

Rappresenta il tipo di file. Fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da**GroupDocs.Merger** , rileva il tipo di file per estensione ecc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Suffisso nome file (incluso il punto ".") ad es. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nome del tipo di file, ad esempio "Documento Microsoft Word". |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Associa l'estensione del file al tipo di file. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Determina se la corrente[`FileType`](../filetype) è uguale a quanto specificato[`FileType`](../filetype) oggetto. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Determina se la corrente[`FileType`](../filetype) è uguale all'oggetto specificato. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Restituisce il codice hash per la corrente[`FileType`](../filetype) oggetto. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Recupera i tipi di file supportati |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Determina se input[`FileType`](../filetype) è il formato di archivio. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Determina se input[`FileType`](../filetype) è il formato immagine. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Determina se input[`FileType`](../filetype) è il formato di testo primitivo. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Determina se due[`FileType`](../filetype) gli oggetti sono gli stessi. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Determina se due[`FileType`](../filetype) gli oggetti non sono gli stessi. |

## Campi

| Nome | Descrizione |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap Image File (.bmp) rappresenta i file utilizzati per archiviare immagini digitali bitmap. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | File compresso Bzip2 (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Il file con valori separati da virgola (.csv) rappresenta file di testo semplice che contengono record di dati con valori separati da virgola. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | I documenti di Microsoft Word (.doc) rappresentano i documenti generati da Microsoft Word o altri documenti di elaborazione testi in formato file binario. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | I file Word Open XML Macro-Enabled Document (.docm) sono documenti generati da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) è un formato ben noto per i documenti Microsoft Word. Introdotto a partire dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è stata modificata da semplice binario a una combinazione di XML e file binari. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | I file Word Document Template (.dot) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) rappresenta il file modello creato con Microsoft Word 2007 o versioni successive. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) è un formato di file di e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è ormai così comune che è supportato da molti e-reader e applicazioni software. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log File (.err) è un file di testo che contiene i messaggi di errore generati da un programma. Ulteriori informazioni su questo formato di file[Qui](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | File in formato di interscambio grafico (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | File compresso G-Zip (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) è l'estensione per le pagine Web create per la visualizzazione nei browser. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | Immagine JPEG (.jpeg) è un tipo di formato immagine che viene salvato utilizzando il metodo di compressione con perdita. L'immagine di output, come risultato della compressione, è un compromesso tra le dimensioni di archiviazione e la qualità dell'immagine. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | Immagine JPEG (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) è un formato di archivio di pagine Web che può essere creato da diverse applicazioni. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) è un formato di archivio di pagine Web che può essere creato da diverse applicazioni. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) rappresenta il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | I file OpenDocument Text Document (.odt) sono tipi di documenti creati con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | I file OneNote Document (.one) vengono creati dall'applicazione Microsoft OneNote. OneNote ti consente di raccogliere informazioni utilizzando l'applicazione come se stessi utilizzando il blocco per appunti per prendere appunti. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument Presentation Template (.otp) rappresenta i file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. Ulteriori informazioni su questo formato file[Qui](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Document Template (.ott) rappresentano documenti template generati da applicazioni conformi al formato standard OpenDocument di OASIS. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) è un formato di file introdotto come standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Ulteriori informazioni su questo file formato[Qui](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) è un tipo di formato di file di immagine raster che utilizza la compressione senza perdita. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) è un file creato utilizzando Microsoft PowerPoint a scopo di presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) è un file creato utilizzando Microsoft PowerPoint 2007 e versioni successive a scopo di presentazione. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) rappresenta un file PowerPoint costituito da una raccolta di diapositive da visualizzare come SlideShow. Specifica il formato di file binario utilizzato da Microsoft PowerPoint 97-2003. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) è un file di presentazione creato con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT che era binario, il formato PPTX si basa sul formato di file di presentazione XML aperto di Microsoft PowerPoint. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | File PostScript (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | File compresso archivio Roshal (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) introdotto e documentato da Microsoft, il Rich Text Format (RTF) rappresenta un metodo di codifica di testo e grafica formattati per l'utilizzo all'interno delle applicazioni. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | File compresso 7-Zip (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Archivio file Unix consolidato (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Source Document (.tex) è un linguaggio che comprende funzionalità di programmazione e markup, utilizzate per impaginare i documenti. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | File immagine con tag (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Formato file immagine con tag (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Il file con valori separati da tabulazioni (.tsv) rappresenta i dati separati da tabulazioni in formato di testo normale. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) rappresenta un documento di testo che contiene testo normale sotto forma di righe. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Rappresenta un tipo di file sconosciuto. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) è un disegno o un grafico creato in Microsoft Visio, ma salvato in formato XML con estensione .VDX. Un file XML di disegno Visio viene creato nel software Visio, sviluppato da Microsoft. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma forniscono anche la possibilità di eseguire macro all'apertura del file. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) rappresenta il formato di file Microsoft Visio introdotto da Microsoft Office 2013 in poi. È stato sviluppato per sostituire il formato di file binario, .VSD, supportato dalle versioni precedenti di Microsoft Visio. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | I file stencil con attivazione macro di Visio (.vssm) sono file stencil di Microsoft Visio che supportano le macro. Un file VSSM, una volta aperto, consente di eseguire le macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) sta disegnando stencil creati con Microsoft Visio 2013 e versioni successive. Il formato file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per la rappresentazione di una varietà di elementi di disegno come raccolta di forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML, Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) sono file modello creati con Microsoft Visio che supportano le macro. A differenza dei file VSDX, i file creati dai modelli VSTM possono eseguire macro sviluppate nel codice Visual Basic for Applications (VBA). Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono il punto di partenza per la creazione di disegni Visio, salvati come file .VSDX, con layout e impostazioni predefiniti. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) fa riferimento a stencil costituiti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX vengono salvati nel formato di file XML ed erano supportati fino a Visio 2013. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) è un modello di disegno di Microsoft Visio che viene salvato su disco in formato file XML. Il modello ha lo scopo di fornire un file con impostazioni di base che possono essere utilizzate per creare più file Visio con le stesse impostazioni. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Componente aggiuntivo con attivazione macro di Excel (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) è un file che può essere creato da Microsoft Excel e da altri programmi di fogli di calcolo simili come OpenOffice Calc o Apple Numbers. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Il formato file foglio di calcolo binario di Excel (.xlsb) specifica il formato di file binario di Excel, che è una raccolta di record e strutture che specificano il contenuto della cartella di lavoro di Excel. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) è un tipo di file Spreasheet che supporta le macro. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) è un formato noto per i documenti Microsoft Excel introdotto da Microsoft con il rilascio di Microsoft Office 2007. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | File modello Excel (.xlt) sono file modello creati con Microsoft Excel, un'applicazione per fogli di calcolo inclusa nella suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT e l'apertura di questi. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Il modello di foglio di calcolo con attivazione macro Excel Open XML (.xltm) rappresenta i file generati da Microsoft Excel come file modello con attivazione macro. I file XLTM sono simili a XLTX nella struttura diversa da quella successiva non supporta la creazione di file modello con macro. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | I file Excel Open XML Spreadsheet Template (.xltx) si basano sulle specifiche del formato di file Office OpenXML. Viene utilizzato per creare un file modello standard che può essere utilizzato per generare file XLSX che presentano le stesse impostazioni specificate nel file XLTX. Ulteriori informazioni su questo formato file[Qui](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | Il file XML Paper Specification (.xps) rappresenta i file di layout di pagina basati su XML Paper Specifications creati da Microsoft. Ulteriori informazioni su questo formato di file[Qui](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | File zippato (.zip) |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sui formati di file supportati da GroupDocs.Merger: [Elenco completo dei formati di documenti supportati](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Ulteriori informazioni su come ottenere i tipi di file supportati nel codice: [Come ottenere i formati di file supportati nel codice](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Guarda anche

* spazio dei nomi [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assemblea [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
