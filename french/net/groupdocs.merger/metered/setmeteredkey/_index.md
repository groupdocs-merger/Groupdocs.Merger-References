---
title: "SetMeteredKey"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Active le produit avec des clés Metered."
type: docs
weight: 20
url: /fr/net/groupdocs.merger/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Active le produit avec des clés Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicKey | String | La clé publique. |
| privateKey | String | La clé privée. |

### Exemples

L'exemple suivant montre comment activer le produit avec des clés Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
