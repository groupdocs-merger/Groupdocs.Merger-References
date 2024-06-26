---
title: SetLicense
second_title: GroupDocs.Merger for .NET API Reference
description: Licenses the component.
type: docs
weight: 20
url: /net/groupdocs.merger/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Licenses the component.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licenseStream | Stream | The license stream. |

### Examples

The following example demonstrates how to set a license passing Stream of the license file.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
    lic.SetLicense(licenseStream);
}
```

### See Also

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## SetLicense(string) {#setlicense_1}

Licenses the component.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licensePath | String | The license path. |

### Examples

The following example demonstrates how to set a license passing a path to the license file.

```csharp
string licensePath = "GroupDocs.Merger.lic";
GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
lic.SetLicense(licensePath);
```

### See Also

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
