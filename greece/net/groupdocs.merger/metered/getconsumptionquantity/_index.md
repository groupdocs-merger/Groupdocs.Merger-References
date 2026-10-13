---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Ανακτά το ποσό των επεξεργασμένων MB."
type: docs
weight: 40
url: /el/net/groupdocs.merger/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Ανακτά το ποσό των επεξεργασμένων MB.

```csharp
public static decimal GetConsumptionQuantity()
```

### Examples

Το παρακάτω παράδειγμα δείχνει πώς να ανακτήσετε την ποσότητα των επεξεργασμένων MB.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
