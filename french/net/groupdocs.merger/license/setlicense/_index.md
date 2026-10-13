---
title: "SetLicense"
second_title: "Référence API de GroupDocs.Merger pour .NET"
description: "Licence le composant."
type: docs
weight: 20
url: /fr/net/groupdocs.merger/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licence le composant.

```csharp
public void SetLicense(Stream licenseStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licenseStream | Stream | Le flux de licence. |

### Exemples

L'exemple suivant montre comment définir une licence en passant le flux du fichier de licence.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
    lic.SetLicense(licenseStream);
}
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## SetLicense(string) {#setlicense_1}

Licence le composant.

```csharp
public void SetLicense(string licensePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| licensePath | String | Le chemin de la licence. |

### Exemples

L'exemple suivant montre comment définir une licence en passant un chemin vers le fichier de licence.

```csharp
string licensePath = "GroupDocs.Merger.lic";
GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
lic.SetLicense(licensePath);
```

### Voir aussi

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.merger.dll -->
