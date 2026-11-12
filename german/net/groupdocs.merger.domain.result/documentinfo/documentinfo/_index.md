---
title: "DocumentInfo"
second_title: "GroupDocs.Merger für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse DocumentInfogroupdocs.merger.domain.result/documentinfo."
type: docs
weight: 10
url: /de/net/groupdocs.merger.domain.result/documentinfo/documentinfo/
---
## DocumentInfo constructor

Initialisiert eine neue Instanz der Klasse [`DocumentInfo`](../../documentinfo).

```csharp
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileType | FileType | Der Typ der Datei. |
| Seiten | IPageInfo[] | Die Liste der anzuzeigenden Seiten. |
| größe | Int64 | Die Größe der Datei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *fileType* null ist. |
| ArgumentNullException | Ausgelöst, wenn *pages* null ist. |

### Siehe auch

* class [FileType](../../../groupdocs.merger.domain/filetype)
* interface [IPageInfo](../../ipageinfo)
* class [DocumentInfo](../../documentinfo)
* namespace [GroupDocs.Merger.Domain.Result](../../../groupdocs.merger.domain.result)
* assembly [GroupDocs.Merger](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.merger.dll -->
