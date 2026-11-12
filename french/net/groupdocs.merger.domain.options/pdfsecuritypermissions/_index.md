---
title: "PdfSecurityPermissions"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Définit les autorisations du document PDF."
type: docs
weight: 610
url: /fr/net/groupdocs.merger.domain.options/pdfsecuritypermissions/
---
## PdfSecurityPermissions enumeration

Définit les autorisations du document PDF.

```csharp
[Flags]
public enum PdfSecurityPermissions
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AllowAll | `0` | Autoriser l'impression, la modification et l'extraction de données. |
| DenyPrinting | `1` | Refuser l'impression. |
| DenyModification | `2` | Refuser la modification du contenu, le remplissage des formulaires, l'ajout ou la modification d'annotations. |
| DenyDataExtraction | `4` | Refuser l'extraction de texte et de graphiques. |
| DenyAll | `7` | Refuser l'impression, la modification du contenu et l'extraction de données. |

### Voir aussi

* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
