---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Ruft die Menge der verwendeten Credits ab"
type: docs
weight: 30
url: /de/net/groupdocs.merger/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Ruft die Menge der verwendeten Credits ab

```csharp
public static decimal GetConsumptionCredit()
```

### Beispiele

Das folgende Beispiel zeigt, wie die Menge der verarbeiteten MB abgerufen wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal usedCredits = Metered.GetConsumptionCredit();
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
