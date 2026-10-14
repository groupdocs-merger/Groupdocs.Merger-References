---
title: "FileType"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Représente le type de fichier."
type: docs
weight: 10
url: /fr/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Représente le type de fichier. Fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par **GroupDocs.Merger**, détecter le type de fichier par extension, etc.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Champs

| Champ | Description |
| --- | --- |
| [Unknown](#Unknown) | Représente un type de fichier inconnu. |
| [ZIP](#ZIP) | Fichier compressé (.zip) |
| [SevenZ](#SevenZ) | Fichier compressé 7-Zip (.7z) |
| [TAR](#TAR) | Archive de fichiers Unix consolidée (.tar) |
| [RAR](#RAR) | Fichier compressé Roshal ARchive (.rar) |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) sont des fichiers de modèle créés avec Microsoft Visio qui prennent en charge les macros. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) sont des fichiers gabarit Microsoft Visio qui offrent la prise en charge des macros. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) fait référence aux gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) est un modèle de dessin Microsoft Visio qui est enregistré sur le disque au format de fichier XML. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) est un dessin ou un graphique créé dans Microsoft Visio, mais enregistré au format XML avec l'extension .VDX. |
| [EPUB](#EPUB) | Open eBook File (.epub) est un format de fichier e‑book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. |
| [BMP](#BMP) | Bitmap Image File (.bmp) représente des fichiers utilisés pour stocker des images numériques bitmap. |
| [JPG](#JPG) | Image JPEG (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) est un type de format d'image qui est enregistré en utilisant la compression avec perte. |
| [PNG](#PNG) | Portable Network Graphic (.png) est un type de format de fichier image raster qui utilise une compression sans perte. |
| [PS](#PS) | Fichier PostScript (.ps) |
| [TIF](#TIF) | Fichier d'image balisée (.tif) |
| [TIFF](#TIFF) | Format de fichier image balisé (.tiff) |
| [GIF](#GIF) | Fichier Graphical Interchange Format (.gif) |
| [SVG](#SVG) | Fichier Scalable Vector Graphics (.svg) |
| [SVGZ](#SVGZ) | Fichier Scalable Vector Graphics compressé (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Le fichier Hypertext Markup Language (.html) est l'extension des pages Web créées pour être affichées dans les navigateurs. |
| [MHT](#MHT) | MHTML Web Archive (.mht) est un format d'archive de pages Web qui peut être créé par un certain nombre d'applications différentes. |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) est un format d'archive de pages Web qui peut être créé par un certain nombre d'applications différentes. |
| [ONE](#ONE) | Les fichiers OneNote Document (.one) sont créés par l'application Microsoft OneNote. |
| [PDF](#PDF) | Portable Document Format File (.pdf) est un format de fichier qui a été introduit comme norme pour la représentation de documents et d'autres supports de référence dans un format indépendant du logiciel applicatif, du matériel ainsi que du système d'exploitation. |
| [XPS](#XPS) | XML Paper Specification File (.xps) représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. |
| [TEX](#TEX) | LaTeX Source Document (.tex) est un langage qui comprend des fonctionnalités de programmation ainsi que de balisage, utilisé pour la composition de documents. |
| [PPT](#PPT) | PowerPoint Presentation (.ppt) représente un fichier PowerPoint qui consiste en une collection de diapositives destinées à être affichées en diaporama. |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) est un fichier de présentation créé avec l'application populaire Microsoft PowerPoint. |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) est un fichier créé avec Microsoft PowerPoint à des fins de diaporama. |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) est un fichier créé avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama. |
| [ODP](#ODP) | OpenDocument Presentation (.odp) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASIS Open. |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) représente les fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. |
| [XLS](#XLS) | Excel Spreadsheet (.xls) est un fichier qui peut être créé par Microsoft Excel ainsi que par d'autres programmes de tableur similaires tels qu'OpenOffice Calc ou Apple Numbers. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) est un type de fichiers de tableur qui prend en charge les macros. |
| [XLSB](#XLSB) | Le format de fichier Excel Binary Spreadsheet (.xlsb) spécifie le Excel Binary File Format, qui est une collection d'enregistrements et de structures définissant le contenu d'un classeur Excel. |
| [CSV](#CSV) | Comma Separated Values File (.csv) représente des fichiers texte simples contenant des enregistrements de données avec des valeurs séparées par des virgules. |
| [TSV](#TSV) | Tab Separated Values File (.tsv) représente des données séparées par des tabulations dans un format texte simple. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods). |
| [XLTM](#XLTM) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) représente les fichiers générés par Microsoft Excel en tant que modèles activés par macro. |
| [XLTX](#XLTX) | Excel Open XML Spreadsheet Template (.xltx) les fichiers sont basés sur les spécifications du format de fichier Office OpenXML. |
| [XLT](#XLT) | Excel Template File (.xlt) sont des fichiers modèle créés avec Microsoft Excel, qui est une application de tableur faisant partie de la suite Microsoft Office. |
| [XLAM](#XLAM) | Module complémentaire Excel activé par macro (.xlam). |
| [DOC](#DOC) | Le document Microsoft Word (.doc) représente les documents générés par Microsoft Word ou d’autres traitements de texte au format binaire. |
| [DOCX](#DOCX) | Le document Microsoft Word Open XML (.docx) est un format bien connu pour les documents Microsoft Word. |
| [DOCM](#DOCM) | Les fichiers Word Open XML activés par macro (.docm) sont des documents générés par Microsoft Word 2007 ou version ultérieure, capables d’exécuter des macros. |
| [DOT](#DOT) | Les fichiers modèle de document Word (.dot) sont des modèles créés par Microsoft Word contenant des paramètres préformatés pour la génération de futurs fichiers DOC ou DOCX. |
| [DOTX](#DOTX) | Les modèles de document Word Open XML (.dotx) sont des fichiers modèles créés par Microsoft Word contenant des paramètres préformatés pour la génération de futurs fichiers DOCX. |
| [DOTM](#DOTM) | Le modèle de document Word Open XML activé par macro (.dotm) représente un fichier modèle créé avec Microsoft Word 2007 ou version ultérieure. |
| [RTF](#RTF) | Le fichier Rich Text Format (.rtf), introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d’encodage du texte formaté et des graphiques pour une utilisation dans les applications. |
| [TXT](#TXT) | Le fichier texte brut (.txt) représente un document texte contenant du texte simple sous forme de lignes. |
| [ERR](#ERR) | Le fichier journal d’erreurs (.err) est un fichier texte contenant les messages d’erreur générés par un programme. |
| [ODT](#ODT) | Les fichiers OpenDocument Text Document (.odt) sont un type de documents créés avec des applications de traitement de texte basées sur le format OpenDocument Text. |
| [OTT](#OTT) | Les modèles de documents OpenDocument (.ott) représentent des documents modèles générés par des applications conformes au format standard OpenDocument de l’OASIS. |
| [WAV](#WAV) | WAV, connu sous le nom de WAVE (Waveform Audio File Format), est un sous-ensemble de la spécification Resource Interchange File Format (RIFF) de Microsoft\\u2019s pour le stockage de fichiers audio numériques. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Nom du type de fichier, p. ex. |
| [getExtension()](#getExtension--) | Suffixe du nom de fichier (y compris le point ".") p. ex. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Mappe l’extension de fichier au type de fichier. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Récupère les types de fichiers pris en charge |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) actuel est identique à l’objet [FileType](../../com.groupdocs.merger.domain/filetype) spécifié. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) actuel est identique à l’objet spécifié. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage de l’objet [FileType](../../com.groupdocs.merger.domain/filetype) actuel. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Détermine si deux objets [FileType](../../com.groupdocs.merger.domain/filetype) sont identiques. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Détermine si deux objets [FileType](../../com.groupdocs.merger.domain/filetype) ne sont pas identiques. |
| [toString()](#toString--) | Renvoie une chaîne qui représente l’objet actuel. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) d’entrée est un format texte primitif. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) d’entrée est un format d’archive. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) d’entrée est un format texte primitif. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Détermine si l'entrée [FileType](../../com.groupdocs.merger.domain/filetype) est un format audio. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Représente un type de fichier inconnu.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Fichier compressé (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


Fichier compressé 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Archive de fichiers Unix consolidée (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Fichier compressé Roshal ARchive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Le fichier de pochoir Visio (.vssx) est un pochoir de dessin créé avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et versions ultérieures. Les fichiers Visio sont connus pour la représentation d'une variété d'éléments de dessin tels qu'une collection de formes, de connecteurs, de diagrammes de flux, de mise en réseau, de diagrammes UML. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Le dessin Visio (.vsdx) représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire, .VSD, qui est pris en charge par les versions antérieures de Microsoft Visio. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Le dessin Visio avec macros activées (.vsdm) est un fichier de dessin créé avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires aux VSDX, mais offrent également la capacité d'exécuter des macros lors de l'ouverture du fichier. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Le modèle de dessin Visio (.vstx) est un fichier de modèle de dessin créé avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX offrent un point de départ pour créer des dessins Visio, enregistrés au format .VSDX, avec une mise en page et des paramètres par défaut. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Le modèle de dessin Visio avec macros activées (.vstm) est un fichier de modèle créé avec Microsoft Visio qui prend en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées en code Visual Basic for Applications (VBA). En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Le fichier de pochoir Visio avec macros activées (.vssm) est un fichier de pochoir Microsoft Visio qui prend en charge les macros. Un fichier VSSM, lorsqu'il est ouvert, permet d'exécuter les macros afin d'obtenir le formatage et le placement souhaités des formes dans un diagramme. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Le fichier de pochoir XML Visio (.vsx) fait référence aux pochoirs composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format XML et étaient pris en charge jusqu'à Visio 2013. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Le fichier de modèle XML Visio (.vtx) est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. Le modèle vise à fournir un fichier avec des paramètres de base pouvant être utilisés pour créer plusieurs fichiers Visio avec les mêmes paramètres. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Le fichier de dessin XML Visio (.vdx) est un dessin ou un diagramme créé dans Microsoft Visio, mais enregistré au format XML avec l'extension .VDX. Un fichier de dessin XML Visio est créé dans le logiciel Visio, développé par Microsoft. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Le fichier Open eBook (.epub) est un format de fichier e-book qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. Ce format est désormais si répandu qu'il est pris en charge par de nombreux lecteurs électroniques et applications logicielles. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Le fichier d'image bitmap (.bmp) représente des fichiers utilisés pour stocker des images numériques bitmap. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


Image JPEG (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


L'image JPEG (.jpeg) est un type de format d'image enregistré à l'aide d'une compression avec perte. L'image résultante, suite à la compression, représente un compromis entre la taille de stockage et la qualité de l'image. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Le Portable Network Graphic (.png) est un type de format de fichier image raster qui utilise une compression sans perte. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


Fichier PostScript (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Fichier d'image balisée (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Format de fichier image balisé (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Fichier Graphical Interchange Format (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Fichier Scalable Vector Graphics (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Fichier Scalable Vector Graphics compressé (.svgz)

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


Le fichier Hypertext Markup Language (.html) est l'extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


L'archive Web MHTML (.mht) est un format d'archive de page Web qui peut être créé par un certain nombre d'applications différentes. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Le fichier MIME HTML (.mhtml) est un format d'archive de page Web qui peut être créé par un certain nombre d'applications différentes. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


Les fichiers OneNote Document (.one) sont créés par l'application Microsoft OneNote. OneNote vous permet de rassembler des informations en utilisant l'application comme si vous utilisiez votre carnet de brouillon pour prendre des notes. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Le fichier Portable Document Format (.pdf) est un format de fichier qui a été introduit comme une norme pour la représentation de documents et d'autres supports de référence dans un format indépendant du logiciel applicatif, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Le fichier XML Paper Specification (.xps) représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


Le document source LaTeX (.tex) est un langage qui comprend des fonctionnalités de programmation ainsi que de balisage, utilisé pour composer des documents. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


La présentation PowerPoint (.ppt) représente un fichier PowerPoint qui consiste en une collection de diapositives affichées sous forme de diaporama. Elle spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


La présentation PowerPoint Open XML (.pptx) est un fichier de présentation créé avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation Open XML de Microsoft PowerPoint. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Le diaporama PowerPoint (.pps) est un fichier créé avec Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Le diaporama PowerPoint Open XML (.ppsx) est un fichier créé avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de diaporama. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Le format de présentation OpenDocument (.odp) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASIS Open. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


Le modèle de présentation OpenDocument (.otp) représente les fichiers de modèle de présentation créés par les applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


La feuille de calcul Excel (.xls) est un fichier qui peut être créé par Microsoft Excel ainsi que par d'autres programmes de tableur similaires tels qu'OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Le classeur Microsoft Excel Open XML (.xlsx) est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Le classeur Excel Open XML avec macros (.xlsm) est un type de fichiers de feuille de calcul qui prend en charge les macros. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Le format de fichier Excel Binary Spreadsheet (.xlsb) spécifie le format de fichier binaire Excel, qui est une collection d'enregistrements et de structures définissant le contenu d'un classeur Excel. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Le fichier de valeurs séparées par des virgules (.csv) représente des fichiers texte simples contenant des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Le fichier de valeurs séparées par des tabulations (.tsv) représente des données séparées par des tabulations dans un format texte simple. En savoir plus sur ce format de fichier [here][].


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


Le modèle de classeur Excel Open XML avec macros (.xltm) représente les fichiers générés par Microsoft Excel en tant que modèles avec macros. Les fichiers XLTM sont similaires aux XLTX sur le plan de la structure, à la différence que ces derniers ne prennent pas en charge la création de modèles avec macros. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Les modèles de classeur Excel Open XML (.xltx) sont basés sur les spécifications du format de fichier Office OpenXML. Ils sont utilisés pour créer un fichier modèle standard qui peut être utilisé pour générer des fichiers XLSX présentant les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Excel Template File (.xlt) sont des fichiers modèles créés avec Microsoft Excel, qui est une application de feuille de calcul faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Module complémentaire Excel activé par macro (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Microsoft Word Document (.doc) représente des documents générés par Microsoft Word ou d'autres traitements de texte au format binaire. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Microsoft Word Open XML Document (.docx) est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée du binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Word Open XML Macro-Enabled Document (.docm) sont des documents générés par Microsoft Word 2007 ou versions ultérieures, avec la capacité d'exécuter des macros. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Word Document Template (.dot) sont des fichiers modèles créés par Microsoft Word afin de disposer de paramètres préformatés pour la génération ultérieure de fichiers DOC ou DOCX. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Word Open XML Document Template (.dotx) sont des fichiers modèles créés par Microsoft Word afin de disposer de paramètres préformatés pour la génération ultérieure de fichiers DOCX. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Word Open XML Macro-Enabled Document Template (.dotm) représente un fichier modèle créé avec Microsoft Word 2007 ou version ultérieure. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Rich Text Format File (.rtf), introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d'encodage du texte formaté et des graphiques pour une utilisation dans les applications. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Plain Text File (.txt) représente un document texte contenant du texte brut sous forme de lignes. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Error Log File (.err) est un fichier texte contenant les messages d'erreur générés par un programme. En savoir plus sur ce format de fichier [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


OpenDocument Text Document (.odt) sont des types de documents créés avec des applications de traitement de texte basées sur le format OpenDocument Text File. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


OpenDocument Document Template (.ott) représente des documents modèles générés par des applications conformes au format standard OpenDocument de l'OASIS. En savoir plus sur ce format de fichier [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, connu sous le nom de WAVE (Waveform Audio File Format), est un sous-ensemble du format Resource Interchange File Format (RIFF) de Microsoft destiné au stockage de fichiers audio numériques. Le format n'applique aucune compression au flux de bits et stocke les enregistrements audio avec différentes fréquences d'échantillonnage et débits. Il a été et reste l'un des formats standards pour les CD audio. En savoir plus sur ce format de fichier  [here][] .


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Nom du type de fichier, par ex. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Suffixe du nom de fichier (y compris le point ".") par ex. ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Mappe l’extension de fichier au type de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| extension | java.lang.String | Extension de fichier (y compris le point "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Récupère les types de fichiers pris en charge

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Retourne la séquence des types de fichiers pris en charge
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) actuel est identique à l’objet [FileType](../../com.groupdocs.merger.domain/filetype) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | L'objet à comparer avec l'objet [FileType](../../com.groupdocs.merger.domain/filetype) actuel. |

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

si

```
obj
```

le paramètre est [FileType](../../com.groupdocs.merger.domain/filetype) et est identique à l'objet [FileType](../../com.groupdocs.merger.domain/filetype) actuel ; sinon,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie le code de hachage de l’objet [FileType](../../com.groupdocs.merger.domain/filetype) actuel.

**Returns:**
int - Un code de hachage pour l'objet [FileType](../../com.groupdocs.merger.domain/filetype) actuel.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Détermine si deux objets [FileType](../../com.groupdocs.merger.domain/filetype) sont identiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Objet [FileType](../../com.groupdocs.merger.domain/filetype) de gauche. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Objet [FileType](../../com.groupdocs.merger.domain/filetype) de droite. |

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

si les deux objets [FileType](../../com.groupdocs.merger.domain/filetype) ne sont pas identiques ; sinon,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l’objet actuel.

**Returns:**
java.lang.String - Une chaîne qui représente l'objet actuel.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) d’entrée est un format texte primitif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | L'objet [FileType](../../com.groupdocs.merger.domain/filetype). |

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

si le [FileType](../../com.groupdocs.merger.domain/filetype) d'entrée est au format archive ; sinon,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Détermine si le [FileType](../../com.groupdocs.merger.domain/filetype) d’entrée est un format texte primitif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | L'objet [FileType](../../com.groupdocs.merger.domain/filetype). |

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

si le [FileType](../../com.groupdocs.merger.domain/filetype) d'entrée est au format audio ; sinon,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
