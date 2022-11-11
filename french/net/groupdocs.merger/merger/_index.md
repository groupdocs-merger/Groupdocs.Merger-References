---
title: Merger
second_title: Référence de l'API GroupDocs.Merger pour .NET
description: Représente la classe principale qui contrôle le processus de fusion de documents.
type: docs
weight: 790
url: /fr/net/groupdocs.merger/merger/
---
## Merger class

Représente la classe principale qui contrôle le processus de fusion de documents.

```csharp
public class Merger : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_4)(Stream) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_8)(string) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Initialise la nouvelle instance de[`Merger`](../merger) classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Protège le document avec un mot de passe. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Applique un nouveau mode d'orientation pour les pages spécifiées. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Dispose des ressources. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Crée un nouveau document avec quelques pages du document source. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Génère un aperçu des pages du document. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Obtient des informations sur les pages du document : leurs tailles, la hauteur maximale de la page, la largeur d'une page avec la hauteur maximale. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Importe le document en pièce jointe ou intégré via Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Vérifie si le document est protégé par un mot de passe. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Joint les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Joint les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Joint les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Joint les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Joint les documents en un seul document. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Joint les documents en un seul document. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Déplace la page vers une nouvelle position dans le document de format connu. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Supprime des pages d'un document de format connu. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Supprime le mot de passe du document. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Faire pivoter les pages du document. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Enregistre le document de résultat dans le flux*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Enregistre le fichier du document de résultat dans*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Enregistre le fichier du document de résultat dans*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Divise le document unique en plusieurs documents. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Divise le document unique en plusieurs documents. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Échange deux pages dans un document de format connu. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Met à jour le mot de passe existant pour le document. |

### Voir également

* espace de noms [GroupDocs.Merger](../../groupdocs.merger)
* Assemblée [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
