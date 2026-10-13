---
title: "SetMeteredKey"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Ενεργοποιεί το προϊόν με κλειδιά Metered."
type: docs
weight: 20
url: /el/net/groupdocs.merger/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Ενεργοποιεί το προϊόν με κλειδιά Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | String | Το δημόσιο κλειδί. |
| privateKey | String | Το ιδιωτικό κλειδί. |

### Examples

Το παρακάτω παράδειγμα δείχνει πώς να ενεργοποιήσετε το προϊόν με κλειδιά Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Δείτε επίσης

* class [Metered](../../metered)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
