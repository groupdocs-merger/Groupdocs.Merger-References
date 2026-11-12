---
title: "PdfSecurityPermissions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Definiert PDF-Dokumentberechtigungen."
type: docs
weight: 610
url: /de/net/groupdocs.merger.domain.options/pdfsecuritypermissions/
---
## PdfSecurityPermissions enumeration

Definiert PDF-Dokumentberechtigungen.

```csharp
[Flags]
public enum PdfSecurityPermissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AllowAll | `0` | Drucken, Ändern und Datenextraktion erlauben. |
| DenyPrinting | `1` | Drucken verweigern. |
| DenyModification | `2` | Inhaltsänderungen, Ausfüllen von Formularen, Hinzufügen oder Ändern von Anmerkungen verweigern. |
| DenyDataExtraction | `4` | Text- und Grafikauszug verweigern. |
| DenyAll | `7` | Drucken, Inhaltsänderungen und Datenextraktion verweigern. |

### Siehe auch

* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
