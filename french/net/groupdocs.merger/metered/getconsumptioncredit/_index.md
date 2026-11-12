---
title: "GetConsumptionCredit"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Récupère le nombre de crédits utilisés"
type: docs
weight: 30
url: /fr/net/groupdocs.merger/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Récupère le nombre de crédits utilisés

```csharp
public static decimal GetConsumptionCredit()
```

### Exemples

L'exemple suivant montre comment récupérer la quantité de Mo traités.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal usedCredits = Metered.GetConsumptionCredit();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
