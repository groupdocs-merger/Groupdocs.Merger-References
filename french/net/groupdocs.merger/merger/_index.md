---
title: "Fusionneur"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Représente la classe principale qui contrôle le processus de fusion des documents."
type: docs
weight: 960
url: /fr/net/groupdocs.merger/merger/
---
## Merger class

Représente la classe principale qui contrôle le processus de fusion des documents.

```csharp
public class Merger : IDisposable, IMerger
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_4)(Stream) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_8)(string) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initialise une nouvelle instance de la classe [`Merger`](../merger). |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Protège le document avec un mot de passe. |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | Applique les modifications du constructeur de pages. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Applique un nouveau mode d'orientation pour les pages spécifiées. |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | Crée un nouveau constructeur de pages avec une collection de documents prédéfinie. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Libère les ressources. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Crée un nouveau document avec certaines pages du document source. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Génère un aperçu des pages du document. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale d'une page, la largeur d'une page avec la hauteur maximale. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importe le document en tant que pièce jointe ou intégré via Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Vérifie si le document est protégé par mot de passe. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | Fusionne les documents en un seul document. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Déplace la page vers une nouvelle position dans le document d'un format connu. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Supprime les pages du document d'un format connu. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Supprime le mot de passe du document. |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | Fait pivoter l'image ou les pages du document. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream, ISaveOptions) | Enregistre le document résultant dans le flux *document*. |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, ISaveOptions) | Enregistre le fichier du document résultant dans *filePath*. |
| [Save](../../groupdocs.merger/merger/save#save_1)(string, bool, ISaveOptions) | Enregistre le fichier du document résultant dans *filePath*. |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Divise le document unique en plusieurs documents. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Divise le document unique en plusieurs documents. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Échange deux pages dans un document au format connu. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Met à jour le mot de passe existant du document. |

### Voir aussi

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
