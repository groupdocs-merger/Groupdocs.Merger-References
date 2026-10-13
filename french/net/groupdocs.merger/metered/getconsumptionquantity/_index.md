---
title: "GetConsumptionQuantity"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Récupère la quantité de Mo traités."
type: docs
weight: 40
url: /fr/net/groupdocs.merger/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Récupère la quantité de Mo traités.

```csharp
public static decimal GetConsumptionQuantity()
```

### Exemples

L'exemple suivant montre comment récupérer la quantité de Mo traités.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
