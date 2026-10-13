---
title: "FromExtension"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Mappe l'extension de fichier au type de fichier."
type: docs
weight: 740
url: /fr/net/groupdocs.merger.domain/filetype/fromextension/
---
## FileType.FromExtension method

Mappe l'extension de fichier au type de fichier.

```csharp
public static FileType FromExtension(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | Extension de fichier (y compris le point \".\"). |

### Valeur de retour

Lorsque le type de fichier est pris en charge, le renvoie ; sinon, renvoie le type de fichier par défaut [`Unknown`](../unknown).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *extension* est null ou chaîne vide. |

### Voir aussi

* class [FileType](../../filetype)
* namespace [GroupDocs.Merger.Domain](../../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
