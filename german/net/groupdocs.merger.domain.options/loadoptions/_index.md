---
title: "LoadOptions"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Bietet Optionen für das Laden von Dokumenten."
type: docs
weight: 450
url: /de/net/groupdocs.merger.domain.options/loadoptions/
---
## LoadOptions class

Bietet Optionen für das Laden von Dokumenten.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [LoadOptions](loadoptions#constructor)(FileType) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_6)(string) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_1)(FileType, FileType) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_4)(FileType, string) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_8)(string, Encoding) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_2)(FileType, FileType, string) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_5)(FileType, string, Encoding) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_3)(FileType, FileType, string, Encoding) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |
| [LoadOptions](loadoptions#constructor_7)(string, FileType, string, Encoding) | Initialisiert eine neue Instanz der [`LoadOptions`](../loadoptions)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Encoding](../../groupdocs.merger.domain.options/loadoptions/encoding) { get; } | Die beim Öffnen von textbasierten Dateien wie [`CSV`](../../groupdocs.merger.domain/filetype/csv) oder [`TXT`](../../groupdocs.merger.domain/filetype/txt) verwendete Kodierung. Der Standardwert ist Default. |
| [Extension](../../groupdocs.merger.domain.options/loadoptions/extension) { get; } | Die Erweiterung der zu initialisierenden Datei. |
| [Password](../../groupdocs.merger.domain.options/loadoptions/password) { get; } | Das Passwort zum Öffnen einer passwortgeschützten Datei. |
| [Type](../../groupdocs.merger.domain.options/loadoptions/type) { get; } | Der Typ der zu ladenden Datei. |

### Siehe auch

* interface [ILoadOptions](../iloadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
