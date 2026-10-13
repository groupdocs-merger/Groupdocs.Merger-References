---
title: "SetLicense"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Lizenziert die Komponente."
type: docs
weight: 20
url: /de/net/groupdocs.merger/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseStream | Stream | Der Lizenz-Stream. |

### Beispiele

Das folgende Beispiel zeigt, wie eine Lizenz gesetzt wird, indem ein Stream der Lizenzdatei übergeben wird.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
    lic.SetLicense(licenseStream);
}
```

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licensePath | String | Der Lizenzpfad. |

### Beispiele

Das folgende Beispiel zeigt, wie eine Lizenz gesetzt wird, indem ein Pfad zur Lizenzdatei übergeben wird.

```csharp
string licensePath = "GroupDocs.Merger.lic";
GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
lic.SetLicense(licensePath);
```

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
