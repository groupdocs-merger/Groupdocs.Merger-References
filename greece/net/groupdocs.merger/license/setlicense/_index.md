---
title: "SetLicense"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Παρέχει άδεια στο στοιχείο."
type: docs
weight: 20
url: /el/net/groupdocs.merger/license/setlicense/
---
## SetLicense(Stream) {#setlicense}

Παρέχει άδεια στο στοιχείο.

```csharp
public void SetLicense(Stream licenseStream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseStream | Stream | Η ροή άδειας. |

### Examples

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας το Stream του αρχείου άδειας.

```csharp
using (FileStream licenseStream = new FileStream("LicenseFile.lic", FileMode.Open))
{
    GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
    lic.SetLicense(licenseStream);
}
```

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

---

## SetLicense(string) {#setlicense_1}

Παρέχει άδεια στο στοιχείο.

```csharp
public void SetLicense(string licensePath)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licensePath | String | Η διαδρομή άδειας. |

### Examples

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας μια διαδρομή στο αρχείο άδειας.

```csharp
string licensePath = "GroupDocs.Merger.lic";
GroupDocs.Merger.License lic = new GroupDocs.Merger.License();
lic.SetLicense(licensePath);
```

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Merger](../../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
