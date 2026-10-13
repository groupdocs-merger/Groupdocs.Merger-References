---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Ανακτά το ποσό των χρησιμοποιημένων μονάδων."
type: docs
weight: 30
url: /el/net/groupdocs.merger/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Ανακτά το ποσό των χρησιμοποιημένων μονάδων.

```csharp
public static decimal GetConsumptionCredit()
```

### Examples

Το παρακάτω παράδειγμα δείχνει πώς να ανακτήσετε την ποσότητα των επεξεργασμένων MB.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal usedCredits = Metered.GetConsumptionCredit();
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
