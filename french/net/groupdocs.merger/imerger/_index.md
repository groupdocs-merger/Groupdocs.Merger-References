---
title: "IMerger"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Interface de la classe principale qui contrôle le processus de fusion de documents."
type: docs
weight: 920
url: /fr/net/groupdocs.merger/imerger/
---
## IMerger interface

Interface de la classe principale qui contrôle le processus de fusion de documents.

```csharp
public interface IMerger
```

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPassword](../../groupdocs.merger/imerger/addpassword)(IAddPasswordOptions) | Protège le document avec un mot de passe. |
| [ChangeOrientation](../../groupdocs.merger/imerger/changeorientation)(IOrientationOptions) | Applique un nouveau mode d'orientation pour les pages spécifiées. |
| [ExtractPages](../../groupdocs.merger/imerger/extractpages)(IExtractOptions) | Crée un nouveau document avec certaines pages du document source. |
| [ImportDocument](../../groupdocs.merger/imerger/importdocument)(IImportDocumentOptions) | Importe le document en tant que pièce jointe ou intégré via Ole. |
| [Join](../../groupdocs.merger/imerger/join#join)(Stream) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_4)(string) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_1)(Stream, IImageJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_2)(Stream, IJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_3)(Stream, IPageJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_5)(string, IImageJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_6)(string, IJoinOptions) | Fusionne les documents en un seul document. |
| [Join](../../groupdocs.merger/imerger/join#join_7)(string, IPageJoinOptions) | Fusionne les documents en un seul document. |
| [MovePage](../../groupdocs.merger/imerger/movepage)(IMoveOptions) | Déplace la page vers une nouvelle position dans le document d'un format connu. |
| [RemovePages](../../groupdocs.merger/imerger/removepages)(IRemoveOptions) | Supprime les pages du document d'un format connu. |
| [RemovePassword](../../groupdocs.merger/imerger/removepassword)() | Supprime le mot de passe du document. |
| [Rotate](../../groupdocs.merger/imerger/rotate)(IRotateOptions) | Faire pivoter les pages du document. |
| [Save](../../groupdocs.merger/imerger/save#save)(Stream, ISaveOptions) | Enregistre le document résultant dans le flux *document*. |
| [Save](../../groupdocs.merger/imerger/save#save_2)(string, ISaveOptions) | Enregistre le fichier du document résultant dans *filePath*. |
| [Save](../../groupdocs.merger/imerger/save#save_1)(string, bool, ISaveOptions) | Enregistre le fichier du document résultant dans *filePath*. |
| [Split](../../groupdocs.merger/imerger/split#split)(ISplitOptions) | Divise le document unique en plusieurs documents. |
| [Split](../../groupdocs.merger/imerger/split#split_1)(ITextSplitOptions) | Divise le document unique en plusieurs documents. |
| [SwapPages](../../groupdocs.merger/imerger/swappages)(ISwapOptions) | Échange deux pages dans un document au format connu. |
| [UpdatePassword](../../groupdocs.merger/imerger/updatepassword)(IUpdatePasswordOptions) | Met à jour le mot de passe existant du document. |

### Voir aussi

* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
