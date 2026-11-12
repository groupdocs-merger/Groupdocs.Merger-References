---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Ruft die Menge der verarbeiteten MBs ab."
type: docs
weight: 40
url: /de/net/groupdocs.merger/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Ruft die Menge der verarbeiteten MBs ab.

```csharp
public static decimal GetConsumptionQuantity()
```

### Beispiele

Das folgende Beispiel zeigt, wie die Menge der verarbeiteten MB abgerufen wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
