---
title: SetMeteredKey
second_title: GroupDocs.Merger for .NET API Reference
description: Activates product with Metered keys.
type: docs
weight: 20
url: /net/groupdocs.merger/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Activates product with Metered keys.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | String | The public key. |
| privateKey | String | The private key. |

### Examples

Following example demonstrates how to activate product with Metered keys.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### See Also

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
