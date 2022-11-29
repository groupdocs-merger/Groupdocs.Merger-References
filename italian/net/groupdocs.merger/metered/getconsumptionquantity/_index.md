---
title: GetConsumptionQuantity
second_title: Riferimento API GroupDocs.Merger per .NET
description: Recupera la quantità di MB elaborati.
type: docs
weight: 40
url: /it/net/groupdocs.merger/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Recupera la quantità di MB elaborati.

```csharp
public static decimal GetConsumptionQuantity()
```

### Esempi

L'esempio seguente mostra come recuperare la quantità di MB elaborati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Guarda anche

* class [Metered](../../metered)
* spazio dei nomi [GroupDocs.Merger](../../metered)
* assemblea [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->