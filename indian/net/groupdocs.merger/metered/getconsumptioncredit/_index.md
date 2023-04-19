---
title: GetConsumptionCredit
second_title: .NET API संदर्भ के लिए GroupDocs.Merger
description: उपयग कए गए क्रेडट क रश पुनर्प्रप्त करत है
type: docs
weight: 30
url: /hi/net/groupdocs.merger/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

उपयोग किए गए क्रेडिट की राशि पुनर्प्राप्त करता है

```csharp
public static decimal GetConsumptionCredit()
```

### उदाहरण

निम्नलिखित उदाहरण प्रदर्शित करता है कि संसाधित एमबी की मात्रा को कैसे पुनः प्राप्त किया जाए।

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal usedCredits = Metered.GetConsumptionCredit();
```

### यह सभी देखें

* class [Metered](../../metered)
* नाम स्थान [GroupDocs.Merger](../../metered)
* सभा [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->