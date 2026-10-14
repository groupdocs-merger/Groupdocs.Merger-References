---
title: "FileType"
second_title: "Il namespace com.groupdocs.merger.domain.builders fornisce i builder."
description: "Rappresenta il tipo di file."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Rappresenta il tipo di file. Fornisce metodi per ottenere l'elenco di tutti i tipi di file supportati da **GroupDocs.Merger**, rilevare il tipo di file per estensione ecc.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Campi

| Campo | Descrizione |
| --- | --- |
| [Unknown](#Unknown) | Rappresenta un tipo di file sconosciuto. |
| [ZIP](#ZIP) | File compresso (.zip) |
| [SevenZ](#SevenZ) | File compresso 7-Zip (.7z) |
| [TAR](#TAR) | Archivio di file Unix consolidato (.tar) |
| [RAR](#RAR) | File compresso Roshal ARchive (.rar) |
| [VSSX](#VSSX) | I file stencil Visio (.vssx) sono stencil di disegno creati con Microsoft Visio 2013 e versioni successive. |
| [VSDX](#VSDX) | Il disegno Visio (.vsdx) rappresenta il formato di file Microsoft Visio introdotto a partire da Microsoft Office 2013. |
| [VSDM](#VSDM) | I file di disegno Visio con macro abilitata (.vsdm) sono file di disegno creati con l'applicazione Microsoft Visio che supporta le macro. |
| [VSTX](#VSTX) | I modelli di disegno Visio (.vstx) sono file modello di disegno creati con Microsoft Visio 2013 e versioni successive. |
| [VSTM](#VSTM) | I modelli di disegno Visio con macro abilitata (.vstm) sono file modello creati con Microsoft Visio che supportano le macro. |
| [VSSM](#VSSM) | I file stencil Visio con macro abilitata (.vssm) sono file stencil Microsoft Visio che forniscono supporto per le macro. |
| [VSX](#VSX) | Il file stencil XML Visio (.vsx) si riferisce a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. |
| [VTX](#VTX) | Il file modello XML Visio (.vtx) è un modello di disegno Microsoft Visio salvato su disco in formato file XML. |
| [VDX](#VDX) | Il file disegno XML Visio (.vdx) è un disegno o diagramma creato in Microsoft Visio, ma salvato in formato XML con estensione .VDX. |
| [EPUB](#EPUB) | Il file eBook Open (.epub) è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. |
| [BMP](#BMP) | Il file immagine bitmap (.bmp) rappresenta file utilizzati per memorizzare immagini digitali bitmap. |
| [JPG](#JPG) | Immagine JPEG (.jpg) |
| [JPEG](#JPEG) | L'immagine JPEG (.jpeg) è un tipo di formato immagine salvato usando il metodo di compressione con perdita. |
| [PNG](#PNG) | Portable Network Graphic (.png) è un tipo di formato di file immagine raster che utilizza compressione senza perdita. |
| [PS](#PS) | File PostScript (.ps) |
| [TIF](#TIF) | File immagine taggato (.tif) |
| [TIFF](#TIFF) | Formato file immagine taggato (.tiff) |
| [GIF](#GIF) | File Graphical Interchange Format (.gif) |
| [SVG](#SVG) | File Scalable Vector Graphics (.svg) |
| [SVGZ](#SVGZ) | File Scalable Vector Graphics compresso (.svgz) |
| [EMF](#EMF) | Metafile migliorato di Windows (.emf) |
| [EMZ](#EMZ) | Metafile compresso migliorato di Windows (.emz) |
| [HTML](#HTML) | Il file Hypertext Markup Language (.html) è l'estensione per le pagine web create per la visualizzazione nei browser. |
| [MHT](#MHT) | MHTML Web Archive (.mht) è un formato di archivio di pagine web che può essere creato da diverse applicazioni. |
| [MHTML](#MHTML) | Il file MIME HTML (.mhtml) è un formato di archivio di pagine web che può essere creato da diverse applicazioni. |
| [ONE](#ONE) | I file OneNote Document (.one) sono creati dall'applicazione Microsoft OneNote. |
| [PDF](#PDF) | Il file Portable Document Format (.pdf) è un formato introdotto come standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. |
| [XPS](#XPS) | Il file XML Paper Specification (.xps) rappresenta file di layout di pagina basati sulle specifiche XML Paper create da Microsoft. |
| [TEX](#TEX) | Il documento sorgente LaTeX (.tex) è un linguaggio che comprende funzionalità di programmazione e di markup, usato per comporre documenti. |
| [PPT](#PPT) | La presentazione PowerPoint (.ppt) rappresenta un file PowerPoint costituito da una raccolta di diapositive per la visualizzazione come presentazione. |
| [PPTX](#PPTX) | La presentazione PowerPoint Open XML (.pptx) è un file di presentazione creato con la popolare applicazione Microsoft PowerPoint. |
| [PPS](#PPS) | Il file PowerPoint Slide Show (.pps) è un file creato con Microsoft PowerPoint per la presentazione. |
| [PPSX](#PPSX) | Il file PowerPoint Open XML Slide Show (.ppsx) è un file creato con Microsoft PowerPoint 2007 e versioni successive per la presentazione. |
| [ODP](#ODP) | Il formato di presentazione OpenDocument (.odp) rappresenta il formato di file di presentazione usato da OpenOffice.org nello standard OASIS Open. |
| [OTP](#OTP) | Il modello di presentazione OpenDocument (.otp) rappresenta i file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. |
| [XLS](#XLS) | Il foglio di calcolo Excel (.xls) è un file che può essere creato da Microsoft Excel così come da altri programmi simili come OpenOffice Calc o Apple Numbers. |
| [XLSX](#XLSX) | Il foglio di calcolo Microsoft Excel Open XML (.xlsx) è un formato noto per i documenti Microsoft Excel, introdotto da Microsoft con il rilascio di Microsoft Office 2007. |
| [XLSM](#XLSM) | Il foglio di calcolo Excel Open XML con macro abilitati (.xlsm) è un tipo di file di foglio di calcolo che supporta le macro. |
| [XLSB](#XLSB) | Il formato di file Excel Binary Spreadsheet (.xlsb) specifica il Excel Binary File Format, una raccolta di record e strutture che definiscono il contenuto della cartella di lavoro Excel. |
| [CSV](#CSV) | Il file valori separati da virgola (.csv) rappresenta file di testo semplice che contengono record di dati con valori separati da virgole. |
| [TSV](#TSV) | Il file valori separati da tabulazione (.tsv) rappresenta dati separati da tabulazioni in formato di testo semplice. |
| [ODS](#ODS) | Foglio di calcolo OpenDocument (.ods). |
| [XLTM](#XLTM) | Il modello di foglio di calcolo Excel Open XML con macro abilitati (.xltm) rappresenta i file generati da Microsoft Excel come modelli con macro abilitate. |
| [XLTX](#XLTX) | I file modello di foglio di calcolo Excel Open XML (.xltx) si basano sulle specifiche del formato di file Office OpenXML. |
| [XLT](#XLT) | Il file modello Excel (.xlt) è un file modello creato con Microsoft Excel, un'applicazione di foglio di calcolo inclusa nella suite Microsoft Office. |
| [XLAM](#XLAM) | Componenti aggiuntivi Excel con macro abilitati (.xlam). |
| [DOC](#DOC) | I documenti Microsoft Word (.doc) rappresentano documenti generati da Microsoft Word o da altri programmi di elaborazione testi in formato binario. |
| [DOCX](#DOCX) | Il documento Microsoft Word Open XML (.docx) è un formato noto per i documenti Microsoft Word. |
| [DOCM](#DOCM) | I file Word Open XML con macro abilitate (.docm) sono documenti generati da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. |
| [DOT](#DOT) | I file modello di documento Word (.dot) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. |
| [DOTX](#DOTX) | I modelli di documento Word Open XML (.dotx) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. |
| [DOTM](#DOTM) | Il modello di documento Word Open XML con macro abilitate (.dotm) rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. |
| [RTF](#RTF) | Il file Rich Text Format (.rtf), introdotto e documentato da Microsoft, rappresenta un metodo di codifica di testo formattato e grafica per l'uso nelle applicazioni. |
| [TXT](#TXT) | Il file di testo semplice (.txt) rappresenta un documento di testo che contiene testo semplice sotto forma di righe. |
| [ERR](#ERR) | Il file di registro errori (.err) è un file di testo che contiene messaggi di errore generati da un programma. |
| [ODT](#ODT) | I file OpenDocument Text Document (.odt) sono un tipo di documento creato con applicazioni di elaborazione testi basate sul formato OpenDocument Text. |
| [OTT](#OTT) | I modelli di documento OpenDocument (.ott) rappresentano documenti modello generati da applicazioni conformi al formato standard OpenDocument dell'OASIS. |
| [WAV](#WAV) | WAV, noto per WAVE (Waveform Audio File Format), è un sottoinsieme della specifica Resource Interchange File Format (RIFF) di Microsoft\\\\u2019s per la memorizzazione di file audio digitali. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Nome del tipo di file, ad es. |
| [getExtension()](#getExtension--) | Suffisso del nome file (incluso il punto \".\") ad es. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mappa l'estensione del file al tipo di file. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Recupera i tipi di file supportati |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Determina se il corrente [FileType](../../com.groupdocs.merger.domain/filetype) è lo stesso dell'oggetto [FileType](../../com.groupdocs.merger.domain/filetype) specificato. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il corrente [FileType](../../com.groupdocs.merger.domain/filetype) è lo stesso dell'oggetto specificato. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per l'oggetto [FileType](../../com.groupdocs.merger.domain/filetype) corrente. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Determina se due oggetti [FileType](../../com.groupdocs.merger.domain/filetype) sono gli stessi. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Determina se due oggetti [FileType](../../com.groupdocs.merger.domain/filetype) non sono gli stessi. |
| [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Determina se il [FileType](../../com.groupdocs.merger.domain/filetype) di input è un formato di testo primitivo. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Determina se il [FileType](../../com.groupdocs.merger.domain/filetype) di input è un formato di archivio. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Determina se il [FileType](../../com.groupdocs.merger.domain/filetype) di input è un formato di testo primitivo. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Determina se l'input [FileType](../../com.groupdocs.merger.domain/filetype) è un formato audio. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Rappresenta un tipo di file sconosciuto.

### ZIP {#ZIP}
```
public static FileType ZIP
```


File compresso (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


File compresso 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Archivio di file Unix consolidato (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


File compresso Roshal ARchive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Il file stencil Visio (.vssx) è un modello di disegno creato con Microsoft Visio 2013 e versioni successive. Il formato file VSSX può essere aperto con Visio 2013 e versioni successive. I file Visio sono noti per la rappresentazione di una varietà di elementi di disegno come collezioni di forme, connettori, diagrammi di flusso, layout di rete, diagrammi UML. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Il disegno Visio (.vsdx) rappresenta il formato file Microsoft Visio introdotto a partire da Microsoft Office 2013. È stato sviluppato per sostituire il formato file binario, .VSD, supportato dalle versioni precedenti di Microsoft Visio. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Il disegno Visio con macro abilitata (.vsdm) è un file di disegno creato con l'applicazione Microsoft Visio che supporta le macro. I file VSDM sono disegni OPC/XML simili a VSDX, ma offrono anche la possibilità di eseguire macro quando il file viene aperto. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Il modello di disegno Visio (.vstx) è un file modello di disegno creato con Microsoft Visio 2013 e versioni successive. Questi file VSTX forniscono un punto di partenza per creare disegni Visio, salvati come file .VSDX, con layout e impostazioni predefinite. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Il modello di disegno Visio con macro abilitata (.vstm) è un file modello creato con Microsoft Visio che supporta le macro. A differenza dei file VSDX, i file creati da modelli VSTM possono eseguire macro sviluppate in codice Visual Basic for Applications (VBA). Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Il file stencil Visio con macro abilitata (.vssm) è un file stencil Microsoft Visio che fornisce supporto per le macro. Un file VSSM, quando aperto, consente di eseguire le macro per ottenere la formattazione e il posizionamento desiderati delle forme in un diagramma. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Il file stencil XML Visio (.vsx) si riferisce a stencil composti da disegni e forme utilizzati per creare diagrammi in Microsoft Visio. I file VSX sono salvati in formato XML e sono stati supportati fino a Visio 2013. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Il file modello XML Visio (.vtx) è un modello di disegno Microsoft Visio salvato su disco in formato XML. Il modello è pensato per fornire un file con impostazioni di base che può essere utilizzato per creare più file Visio con le stesse impostazioni. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Il file XML di disegno Visio (.vdx) è un disegno o diagramma creato in Microsoft Visio, ma salvato in formato XML con estensione .VDX. Un file XML di disegno Visio è creato nel software Visio, sviluppato da Microsoft. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Il file eBook Open (.epub) è un formato di file e-book che fornisce un formato di pubblicazione digitale standard per editori e consumatori. Il formato è ormai così comune da essere supportato da molti e-reader e applicazioni software. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Il file immagine bitmap (.bmp) rappresenta file utilizzati per memorizzare immagini digitali bitmap. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


Immagine JPEG (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


L'immagine JPEG (.jpeg) è un tipo di formato immagine salvato mediante compressione con perdita. L'immagine risultante, a seguito della compressione, è un compromesso tra dimensione di archiviazione e qualità dell'immagine. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Il Portable Network Graphic (.png) è un tipo di formato di file immagine raster che utilizza compressione senza perdita. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


File PostScript (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


File immagine taggato (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Formato file immagine taggato (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


File Graphical Interchange Format (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


File Scalable Vector Graphics (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


File Scalable Vector Graphics compresso (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Metafile migliorato di Windows (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Metafile compresso migliorato di Windows (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Il file Hypertext Markup Language (.html) è l'estensione per pagine web create per la visualizzazione nei browser. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


L'archivio web MHTML (.mht) è un formato di archivio di pagine web che può essere creato da diverse applicazioni. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Il file MIME HTML (.mhtml) è un formato di archivio di pagine web che può essere creato da diverse applicazioni. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


I file OneNote Document (.one) sono creati dall'applicazione Microsoft OneNote. OneNote ti consente di raccogliere informazioni usando l'applicazione come se stessi usando il tuo blocco note per prendere appunti. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Il file Portable Document Format (.pdf) è un formato di file che è stato introdotto come standard per la rappresentazione di documenti e altri materiali di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Il file XML Paper Specification (.xps) rappresenta file di layout di pagina basati sulle Specifiche XML Paper create da Microsoft. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


Il documento sorgente LaTeX (.tex) è un linguaggio che comprende funzionalità di programmazione e di markup, utilizzato per impaginare documenti. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


La presentazione PowerPoint (.ppt) rappresenta un file PowerPoint che consiste in una raccolta di diapositive da visualizzare come presentazione. Specifica il formato binario utilizzato da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


La presentazione PowerPoint Open XML (.pptx) è un file di presentazione creato con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato PPT, che era binario, il formato PPTX si basa sul formato di presentazione Open XML di Microsoft PowerPoint. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Il file PowerPoint Slide Show (.pps) è un file creato con Microsoft PowerPoint per la presentazione. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Il file PowerPoint Open XML Slide Show (.ppsx) è un file creato con Microsoft PowerPoint 2007 e versioni successive per la presentazione. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Il formato di presentazione OpenDocument (.odp) rappresenta il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASIS Open. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


Il modello di presentazione OpenDocument (.otp) rappresenta i file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Il foglio di calcolo Excel (.xls) è un file che può essere creato da Microsoft Excel così come da altri programmi simili come OpenOffice Calc o Apple Numbers. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Il foglio di calcolo Microsoft Excel Open XML (.xlsx) è un formato noto per i documenti Microsoft Excel, introdotto da Microsoft con il rilascio di Microsoft Office 2007. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Il foglio di calcolo Excel Open XML abilitato alle macro (.xlsm) è un tipo di file di foglio di calcolo che supporta le macro. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Il formato di file Excel Binary Spreadsheet (.xlsb) specifica il Excel Binary File Format, una raccolta di record e strutture che definiscono il contenuto di una cartella di lavoro Excel. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Il file valori separati da virgola (.csv) rappresenta file di testo semplice che contengono record di dati con valori separati da virgola. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Il file valori separati da tabulazione (.tsv) rappresenta dati separati da tabulazioni in formato di testo semplice. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Foglio di calcolo OpenDocument (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Il modello di foglio di calcolo Excel Open XML abilitato alle macro (.xltm) rappresenta i file generati da Microsoft Excel come modelli abilitati alle macro. I file XLTM sono simili a XLTX nella struttura, tranne per il fatto che quest'ultimo non supporta la creazione di modelli con macro. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


I file modello di foglio di calcolo Excel Open XML (.xltx) sono basati sulle specifiche del formato file Office OpenXML. Vengono utilizzati per creare un modello standard che può essere impiegato per generare file XLSX con le stesse impostazioni specificate nel file XLTX. Scopri di più su questo formato di file [qui][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


I file modello Excel (.xlt) sono file modello creati con Microsoft Excel, che è un'applicazione di foglio di calcolo inclusa nella suite Microsoft Office. Microsoft Office 97-2003 supportava la creazione di nuovi file XLT così come l'apertura di questi. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Componenti aggiuntivi Excel con macro abilitati (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


I documenti Microsoft Word (.doc) rappresentano documenti generati da Microsoft Word o da altri programmi di elaborazione testi in formato binario. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Il documento Microsoft Word Open XML (.docx) è un formato noto per i documenti Microsoft Word. Introdotto dal 2007 con il rilascio di Microsoft Office 2007, la struttura di questo nuovo formato di documento è passata da binario puro a una combinazione di file XML e binari. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


I file Word Open XML Macro-Enabled Document (.docm) sono documenti generati da Microsoft Word 2007 o versioni successive con la possibilità di eseguire macro. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


I file Word Document Template (.dot) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOC o DOCX. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


I file Word Open XML Document Template (.dotx) sono file modello creati da Microsoft Word per avere impostazioni preformattate per la generazione di ulteriori file DOCX. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Il Word Open XML Macro-Enabled Document Template (.dotm) rappresenta un file modello creato con Microsoft Word 2007 o versioni successive. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Il file Rich Text Format (.rtf), introdotto e documentato da Microsoft, rappresenta un metodo di codifica di testo formattato e grafica per l'uso all'interno delle applicazioni. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Il file Plain Text (.txt) rappresenta un documento di testo che contiene testo semplice sotto forma di righe. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Il file Error Log (.err) è un file di testo che contiene messaggi di errore generati da un programma. Scopri di più su questo formato di file [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


I file OpenDocument Text Document (.odt) sono un tipo di documento creati con applicazioni di elaborazione testi basate sul formato OpenDocument Text File. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


I file OpenDocument Document Template (.ott) rappresentano documenti modello generati da applicazioni conformi al formato standard OpenDocument dell'OASIS. Scopri di più su questo formato di file [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, noto per WAVE (Waveform Audio File Format), è un sottoinsieme della specifica Resource Interchange File Format (RIFF) di Microsoft per la memorizzazione di file audio digitali. Il formato non applica alcuna compressione al flusso di bit e memorizza le registrazioni audio con diverse frequenze di campionamento e bitrate. È stato ed è uno dei formati standard per i CD audio. Scopri di più su questo formato di file  [here][] .


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Nome del tipo di file, ad es. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Suffisso del nome file (incluso il punto ".") ad es. ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Mappa l'estensione del file al tipo di file.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| estensione | java.lang.String | Estensione del file (incluso il punto "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Recupera i tipi di file supportati

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Restituisce la sequenza dei tipi di file supportati
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Determina se il corrente [FileType](../../com.groupdocs.merger.domain/filetype) è lo stesso dell'oggetto [FileType](../../com.groupdocs.merger.domain/filetype) specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | L'oggetto da confrontare con l'attuale oggetto [FileType](../../com.groupdocs.merger.domain/filetype). |

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

if

```
obj
```

il parametro è [FileType](../../com.groupdocs.merger.domain/filetype) ed è lo stesso dell'attuale oggetto [FileType](../../com.groupdocs.merger.domain/filetype); altrimenti,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per l'oggetto [FileType](../../com.groupdocs.merger.domain/filetype) corrente.

**Returns:**
int - Un codice hash per l'attuale oggetto [FileType](../../com.groupdocs.merger.domain/filetype).
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Determina se due oggetti [FileType](../../com.groupdocs.merger.domain/filetype) sono gli stessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Oggetto [FileType](../../com.groupdocs.merger.domain/filetype) sinistro. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Oggetto [FileType](../../com.groupdocs.merger.domain/filetype) destro. |

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

se entrambi gli oggetti [FileType](../../com.groupdocs.merger.domain/filetype) non sono uguali; altrimenti,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
java.lang.String - Una stringa che rappresenta l'oggetto corrente.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Determina se il [FileType](../../com.groupdocs.merger.domain/filetype) di input è un formato di testo primitivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | L'oggetto [FileType](../../com.groupdocs.merger.domain/filetype). |

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

se l'input [FileType](../../com.groupdocs.merger.domain/filetype) è in formato archivio; altrimenti,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Determina se il [FileType](../../com.groupdocs.merger.domain/filetype) di input è un formato di testo primitivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | L'oggetto [FileType](../../com.groupdocs.merger.domain/filetype). |

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

se l'input [FileType](../../com.groupdocs.merger.domain/filetype) è in formato audio; altrimenti,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
