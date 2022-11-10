---
title: FileType
second_title: Référence de l'API GroupDocs.Merger pour .NET
description: Représente le type de fichier. Fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge parGroupDocs.MergerGroupDocs.Merger  détecte le type de fichier par extension etc.
type: docs
weight: 100
url: /fr/net/groupdocs.merger.domain/filetype/
---
## FileType class

Représente le type de fichier. Fournit des méthodes pour obtenir la liste de tous les types de fichiers pris en charge par**GroupDocs.MergerGroupDocs.Merger** , détecte le type de fichier par extension, etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Suffixe du nom de fichier (y compris le point "."), par exemple ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nom du type de fichier, par exemple "Document Microsoft Word". |

## Méthodes

| Nom | La description |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Mappe l'extension de fichier au type de fichier. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Détermine si le courant[`FileType`](../filetype) est le même que celui spécifié[`FileType`](../filetype) objet. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Détermine si le courant[`FileType`](../filetype) est le même que l'objet spécifié. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Renvoie le code de hachage pour le courant[`FileType`](../filetype) objet. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Récupère les types de fichiers pris en charge |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Détermine si l'entrée[`FileType`](../filetype) est un format de texte primitif. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Détermine si l'entrée[`FileType`](../filetype) est un format de texte primitif. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Détermine si deux[`FileType`](../filetype) les objets sont les mêmes. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Détermine si deux[`FileType`](../filetype) les objets ne sont pas les mêmes. |

## Des champs

| Nom | La description |
| --- | --- |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Fichier de valeurs séparées par des virgules (.csv) représente des fichiers en texte brut contenant des enregistrements de données avec des valeurs séparées par des virgules. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Document Microsoft Word (.doc) représente des documents générés par Microsoft Word ou d'autres documents de traitement de texte au format de fichier binaire. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Les fichiers Word Open XML Macro-Enabled Document (.docm) sont des documents générés par Microsoft Word 2007 ou version ultérieure avec la possibilité d'exécuter des macros. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) est un format bien connu pour les documents Microsoft Word. Introduit à partir de 2007 avec la sortie de Microsoft Office 2007, la structure de ce nouveau format de document est passée de binaire simple à une combinaison de fichiers XML et binaires. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Les fichiers de modèle de document Word (.dot) sont des fichiers de modèle créés par Microsoft Word pour avoir des paramètres préformatés pour la génération d'autres fichiers DOC ou DOCX. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) représente un fichier de modèle créé avec Microsoft Word 2007 ou une version ultérieure. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) sont des fichiers modèles créés par Microsoft Word pour avoir des paramètres pré-formatés pour la génération d'autres fichiers DOCX. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) est un format de fichier de livre électronique qui fournit un format de publication numérique standard pour les éditeurs et les consommateurs. Le format est maintenant si courant qu'il est pris en charge par de nombreux lecteurs électroniques et applications logicielles. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log File (.err) est un fichier texte qui contient les messages d'erreur générés par un programme. En savoir plus sur ce format de fichier[ici](https://fileinfo.com/extension/err) . |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) est l'extension des pages Web créées pour être affichées dans les navigateurs. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/web/html) . |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) est un format d'archive de page Web qui peut être créé par un certain nombre d'applications différentes. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) est un format d'archive de page Web qui peut être créé par un certain nombre d'applications différentes. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) représente le format de fichier de présentation utilisé par OpenOffice.org dans la norme OASISOpen. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | Feuille de calcul OpenDocument (.ods) En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | Les fichiers de document texte OpenDocument (.odt) sont des types de documents créés avec des applications de traitement de texte basées sur le format de fichier texte OpenDocument. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | Les fichiers OneNote Document (.one) sont créés par l'application Microsoft OneNote. OneNote vous permet de collecter des informations à l'aide de l'application comme si vous utilisiez votre bloc-notes pour prendre des notes. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | OpenDocument Presentation Template (.otp) représente les fichiers de modèle de présentation créés par des applications au format standard OASIS OpenDocument. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | OpenDocument Document Template (.ott) représente les modèles de documents générés par les applications conformément au format standard OpenDocument d'OASIS. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Portable Document Format File (.pdf) est un format de fichier qui devait être introduit comme norme pour la représentation de documents et d'autres documents de référence dans un format indépendant du logiciel d'application, du matériel ainsi que du système d'exploitation. En savoir plus sur ce fichier format[ici](https://docs.fileformat.com/view/pdf) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | Diaporama PowerPoint (.pps) est un fichier créé à l'aide de Microsoft PowerPoint à des fins de diaporama. La lecture et la création de fichiers PPS sont prises en charge par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) est un fichier créé à l'aide de Microsoft PowerPoint 2007 et supérieur à des fins de diaporama. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | Présentation PowerPoint (.ppt) représente un fichier PowerPoint composé d'une collection de diapositives à afficher sous forme de diaporama. Il spécifie le format de fichier binaire utilisé par Microsoft PowerPoint 97-2003. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) est un fichier de présentation créé avec l'application populaire Microsoft PowerPoint. Contrairement à la version précédente du format de fichier de présentation PPT qui était binaire, le format PPTX est basé sur le format de fichier de présentation XML ouvert de Microsoft PowerPoint. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | Fichier PostScript (.ps) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) introduit et documenté par Microsoft, le format RTF (Rich Text Format) représente une méthode de codage de texte formaté et de graphiques à utiliser dans les applications. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/rtf) . |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Source Document (.tex) est un langage qui comprend la programmation ainsi que des fonctionnalités de balisage, utilisé pour composer des documents. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/page-description-language/tex) . |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Fichier de valeurs séparées par des tabulations (.tsv) représente les données séparées par des tabulations au format texte brut. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Fichier de texte brut (.txt) représente un document texte contenant du texte brut sous forme de lignes. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Représente un type de fichier inconnu. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Le fichier XML de dessin Visio (.vdx) est un dessin ou un graphique créé dans Microsoft Visio, mais enregistré au format XML avec l'extension .VDX. Un fichier XML de dessin Visio est créé dans le logiciel Visio, développé par Microsoft. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) sont des fichiers de dessin créés avec l'application Microsoft Visio qui prend en charge les macros. Les fichiers VSDM sont des dessins OPC/XML similaires à VSDX, mais offrent également la possibilité d'exécuter des macros lorsque le fichier est ouvert. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) représente le format de fichier Microsoft Visio introduit à partir de Microsoft Office 2013. Il a été développé pour remplacer le format de fichier binaire, .VSD, qui est pris en charge par les versions antérieures de Microsoft Visio. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) sont des fichiers Microsoft Visio Stencil qui prennent en charge les macros. Un fichier VSSM lorsqu'il est ouvert permet d'exécuter les macros pour obtenir le formatage et le placement souhaités des formes dans un diagramme. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) sont des gabarits de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Le format de fichier VSSX peut être ouvert avec Visio 2013 et supérieur. Les fichiers Visio sont connus pour la représentation d'une variété d'éléments de dessin tels que la collection de formes, les connecteurs, les organigrammes, la disposition du réseau, les diagrammes UML, En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) sont des fichiers modèles créés avec Microsoft Visio qui prennent en charge les macros. Contrairement aux fichiers VSDX, les fichiers créés à partir de modèles VSTM peuvent exécuter des macros développées dans le code Visual Basic pour Applications (VBA). En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) sont des fichiers de modèle de dessin créés avec Microsoft Visio 2013 et versions ultérieures. Ces fichiers VSTX fournissent un point de départ pour la création de dessins Visio, enregistrés en tant que fichiers .VSDX, avec la mise en page et les paramètres par défaut. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) fait référence à des gabarits composés de dessins et de formes utilisés pour créer des diagrammes dans Microsoft Visio. Les fichiers VSX sont enregistrés au format de fichier XML et étaient pris en charge jusqu'à Visio 2013. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) est un modèle de dessin Microsoft Visio qui est enregistré sur le disque au format de fichier XML. Le modèle vise à fournir un fichier avec des paramètres de base pouvant être utilisés pour créer plusieurs fichiers Visio avec les mêmes paramètres. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Macro complémentaire Excel (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) est un fichier qui peut être créé par Microsoft Excel ainsi que par d'autres tableurs similaires tels que OpenOffice Calc ou Apple Numbers. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Le format de fichier Excel Binary Spreadsheet (.xlsb) spécifie le format de fichier binaire Excel, qui est un ensemble d'enregistrements et de structures qui spécifient le contenu du classeur Excel. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) est un type de fichier de feuille de calcul qui prend en charge les macros. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) est un format bien connu pour les documents Microsoft Excel qui a été introduit par Microsoft avec la sortie de Microsoft Office 2007. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Fichier de modèle Excel (.xlt) sont des fichiers de modèle créés avec Microsoft Excel qui est une application de feuille de calcul qui fait partie de la suite Microsoft Office. Microsoft Office 97-2003 prenait en charge la création de nouveaux fichiers XLT ainsi que leur ouverture. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) représente les fichiers générés par Microsoft Excel en tant que fichiers modèles prenant en charge les macros. Les fichiers XLTM sont similaires à XLTX dans leur structure, sauf que ce dernier ne prend pas en charge la création de fichiers modèles avec des macros. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Les fichiers Excel Open XML Spreadsheet Template (.xltx) sont basés sur les spécifications de format de fichier Office OpenXML. Il est utilisé pour créer un fichier de modèle standard qui peut être utilisé pour générer des fichiers XLSX qui présentent les mêmes paramètres que ceux spécifiés dans le fichier XLTX. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) représente les fichiers de mise en page basés sur les spécifications XML Paper Specifications créées par Microsoft. En savoir plus sur ce format de fichier[ici](https://docs.fileformat.com/page-description-language/xps) . |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les formats de fichiers pris en charge par GroupDocs.Merger : [Liste complète des formats de documents pris en charge](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* En savoir plus sur l'obtention des types de fichiers pris en charge dans le code : [Comment obtenir les formats de fichiers pris en charge dans le code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Voir également

* espace de noms [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* Assemblée [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
