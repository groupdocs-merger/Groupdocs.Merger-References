---
title: "FileType"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Représente le type de fichier. Fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par GroupDocs.Merger, détecter le type de fichier par extension, etc."
type: docs
weight: 110
url: /fr/net/groupdocs.merger.domain/filetype/
---
## FileType class

Représente le type de fichier. Fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par **GroupDocs.Merger**, détecter le type de fichier par extension, etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Suffixe du nom de fichier (y compris le point ".") par ex. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nom du type de fichier, par ex. "Microsoft Word Document". |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Mappe l'extension de fichier au type de fichier. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Détermine si le [`FileType`](../filetype) actuel est le même que l'objet [`FileType`](../filetype) spécifié. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Détermine si le [`FileType`](../filetype) actuel est le même que l'objet spécifié. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Renvoie le code de hachage pour l'objet [`FileType`](../filetype) actuel. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Récupère les types de fichiers pris en charge |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Détermine si le [`FileType`](../filetype) d'entrée est un format d'archive. |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | Détermine si le [`FileType`](../filetype) d'entrée est un format audio. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Détermine si le [`FileType`](../filetype) d'entrée est un format image. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Détermine si le [`FileType`](../filetype) d'entrée est un format texte primitif. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Détermine si deux objets [`FileType`](../filetype) sont identiques. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Détermine si deux objets [`FileType`](../filetype) ne sont pas identiques. |

## Champs

| Nom | Description |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | Le fichier image bitmap (.bmp) représente des fichiers utilisés pour stocker des images numériques bitmap. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Fichier compressé Bzip2 (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | Le fichier valeurs séparées par des virgules (.csv) représente des fichiers texte simples contenant des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/csv). |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Le document Microsoft Word (.doc) représente des documents générés par Microsoft Word ou d'autres traitements de texte au format de fichier binaire. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | Les fichiers Word Open XML Macro-Enabled Document (.docm) sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la capacité d’exécuter des macros. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Le Microsoft Word Open XML Document (.docx) est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée du binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | Les fichiers Word Document Template (.dot) sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOC ou DOCX. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Le Word Open XML Macro-Enabled Document Template (.dotm) représente un fichier modèle créé avec Microsoft Word 2007 ou version ultérieure. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Les fichiers Word Open XML Document Template (.dotx) sont des modèles créés par Microsoft Word pour disposer de paramètres préformatés en vue de la génération de futurs fichiers DOCX. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Metafile amélioré Windows (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Metafile amélioré compressé Windows (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Le fichier Open eBook (.epub) est un format de livre numérique qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. Ce format est désormais si répandu qu’il est pris en charge par de nombreux lecteurs électroniques et applications logicielles. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/ebook/epub). |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | Le fichier journal d’erreurs (.err) est un fichier texte contenant les messages d’erreur générés par un programme. En savoir plus sur ce format de fichier [ici](https://fileinfo.com/extension/err). |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | Fichier Format d'échange graphique (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | Fichier compressé G-Zip (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Le fichier Hypertext Markup Language (.html) est l’extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/web/html). |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | L’image JPEG (.jpeg) est un type de format d’image enregistré en utilisant une compression avec perte. L’image résultante, en raison de la compression, représente un compromis entre la taille de stockage et la qualité de l’image. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | Image JPEG (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | L’archive Web MHTML (.mht) est un format d’archive de page Web qui peut être créé par plusieurs applications différentes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/web/mhtml). |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | Le fichier MIME HTML (.mhtml) est un format d’archive de page Web qui peut être créé par plusieurs applications différentes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/web/mhtml). |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | Les fichiers avec l’extension .mp3 sont des formats de fichiers audio numériquement encodés, basés officiellement sur le MPEG‑1 Audio Layer III ou le MPEG‑2 Audio Layer III. Ils ont été développés par le Moving Picture Experts Group (MPEG) qui utilise la compression audio Layer 3. La compression obtenue avec le format de fichier MP3 représente 1/10 de la taille des fichiers .WAV ou .AIF. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/audio/mp3). |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | Les fichiers OpenDocument Text Document (.odt) sont des types de documents créés avec des applications de traitement de texte basées sur le format OpenDocument Text File. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/odt). |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | Les fichiers OneNote Document (.one) sont créés par l'application Microsoft OneNote. OneNote vous permet de rassembler des informations en utilisant l'application comme si vous utilisiez votre bloc-notes pour prendre des notes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/note-taking/one). |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | Le modèle de présentation OpenDocument (.otp) représente les fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/presentation/otp). |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | Le modèle de document OpenDocument (.ott) représente les documents modèles générés par des applications conformes au format standard OpenDocument d'OASIS. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/ott). |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | Le fichier Portable Document Format (.pdf) est un format de fichier qui a été introduit comme norme pour la représentation de documents et d'autres supports de référence dans un format indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/view/pdf). |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Le Portable Network Graphic (.png) est un type de format de fichier image raster qui utilise une compression sans perte. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/png). |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | Modèle de présentation PowerPoint Open XML avec macros activées (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | Modèle de présentation PowerPoint Open XML (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | Le diaporama PowerPoint (.pps) est un fichier créé avec Microsoft PowerPoint à des fins de présentation. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | Diapositive PowerPoint Open XML avec macros activées (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | Le diaporama PowerPoint Open XML (.ppsx) est un fichier créé avec Microsoft PowerPoint 2007 et versions ultérieures à des fins de présentation. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | La présentation PowerPoint (.ppt) représente un fichier PowerPoint qui consiste en une collection de diapositives affichées sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | Présentation PowerPoint Open XML avec macros activées |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | La présentation PowerPoint Open XML (.pptx) est un fichier de présentation créé avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de présentation Open XML de Microsoft PowerPoint. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | Fichier PostScript (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Fichier compressé Roshal ARchive (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Le fichier Rich Text Format (.rtf) introduit et documenté par Microsoft, le Rich Text Format (RTF) représente une méthode d'encodage du texte formaté et des graphiques pour une utilisation au sein des applications. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/rtf). |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | Fichier compressé 7-Zip (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Fichier Scalable Vector Graphics (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Fichier compressé Scalable Vector Graphics (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | Archive Unix consolidée (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | Le document source LaTeX (.tex) est un langage qui comprend des fonctionnalités de programmation ainsi que de balisage, utilisé pour composer des documents. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/page-description-language/tex). |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | Fichier d'image balisée (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Format de fichier d'image balisée (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Le fichier de valeurs séparées par des tabulations (.tsv) représente des données séparées par des tabulations dans un format texte brut. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Le fichier texte brut (.txt) représente un document texte contenant du texte simple sous forme de lignes. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Représente un type de fichier inconnu. |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) est un dessin ou un diagramme créé dans Microsoft Visio, mais enregistré au format XML avec l'extension .VDX. Un fichier Visio Drawing XML est créé dans le logiciel Visio, développé par Microsoft. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | Visio Drawing File (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires aux VSDX, mais offrent également la possibilité d'exécuter des macros lors de l'ouverture du fichier. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire .VSD, pris en charge par les versions antérieures de Microsoft Visio. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | Visio Stencil File(.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) sont des fichiers de gabarit Microsoft Visio qui offrent la prise en charge des macros. Un fichier VSSM, lorsqu'il est ouvert, permet d'exécuter les macros afin d'obtenir le formatage et le placement souhaités des formes dans un diagramme. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et versions ultérieures. Les fichiers Visio sont connus pour la représentation d'une variété d'éléments de dessin tels que des collections de formes, des connecteurs, des organigrammes, des agencements réseau, des diagrammes UML. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Visio Drawing Template (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) sont des fichiers de modèle créés avec Microsoft Visio qui prennent en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées en code Visual Basic for Applications (VBA). En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX offrent un point de départ pour créer des dessins Visio, enregistrés au format .VSDX, avec une mise en page et des paramètres par défaut. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) désigne des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format XML et étaient pris en charge jusqu'à Visio 2013. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) est un modèle de dessin Microsoft Visio enregistré sur le disque au format XML. Ce modèle vise à fournir un fichier avec des paramètres de base pouvant être utilisés pour créer plusieurs fichiers Visio avec les mêmes réglages. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV, connu sous le nom de WAVE (Waveform Audio File Format), est un sous-ensemble de la spécification Resource Interchange File Format (RIFF) de Microsoft pour le stockage de fichiers audio numériques. Le format n’applique aucune compression au flux de bits et stocke les enregistrements audio avec différentes fréquences d’échantillonnage et débits. Il a été et reste l’un des formats standards pour les CD audio. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Excel Macro-Enabled Add-In (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) est un fichier qui peut être créé par Microsoft Excel ainsi que par d’autres programmes de tableur similaires tels qu’OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) spécifie le format de fichier Excel Binary File Format, qui est une collection d’enregistrements et de structures définissant le contenu d’un classeur Excel. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) est un type de fichiers de feuille de calcul qui prend en charge les macros. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) sont des fichiers modèle créés avec Microsoft Excel, qui est une application de feuille de calcul faisant partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) représente des fichiers générés par Microsoft Excel en tant que modèles activés par des macros. Les fichiers XLTM sont similaires aux XLTX sur le plan de la structure, à la différence que ces derniers ne prennent pas en charge la création de modèles avec des macros. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Les fichiers Excel Open XML Spreadsheet Template (.xltx) sont basés sur les spécifications du format de fichier Office OpenXML. Ils sont utilisés pour créer un fichier modèle standard qui peut être utilisé pour générer des fichiers XLSX présentant les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/spreadsheet/xltx). |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) représente des fichiers de mise en page basés sur les spécifications XML Paper créées par Microsoft. En savoir plus sur ce format de fichier [ici](https://docs.fileformat.com/page-description-language/xps). |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | Fichier compressé (.zip) |

### Remarques

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Voir aussi

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
