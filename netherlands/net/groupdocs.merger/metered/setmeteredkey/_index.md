---
title: SetMeteredKey
second_title: GroupDocs.Merger voor .NET API-referentie
description: Activeert product met gemeten toetsen.
type: docs
weight: 20
url: /nl/net/groupdocs.merger/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Activeert product met gemeten toetsen.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | String | De publieke sleutel. |
| privateKey | String | De privésleutel. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u het product activeert met gemeten sleutels.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Zie ook

* class [Metered](../../metered)
* naamruimte [GroupDocs.Merger](../../metered)
* montage [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->