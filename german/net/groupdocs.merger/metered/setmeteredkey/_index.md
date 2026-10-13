---
title: "SetMeteredKey"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Aktiviert das Produkt mit Metered-Schlüsseln."
type: docs
weight: 20
url: /de/net/groupdocs.merger/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Aktiviert das Produkt mit Metered-Schlüsseln.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | Der öffentliche Schlüssel. |
| privateKey | String | Der private Schlüssel. |

### Beispiele

Das folgende Beispiel zeigt, wie das Produkt mit Metered-Schlüsseln aktiviert wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
