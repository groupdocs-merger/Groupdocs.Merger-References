---
title: DocumentInfo
second_title: GroupDocs.Merger for .NET API Reference
description: Αρχικοποιεί νέα παρουσία τουDocumentInfogroupdocs.merger.domain.result/documentinfo τάξη.
type: docs
weight: 10
url: /el/net/groupdocs.merger.domain.result/documentinfo/documentinfo/
---
## DocumentInfo constructor

Αρχικοποιεί νέα παρουσία του[`DocumentInfo`](../../documentinfo) τάξη.

```csharp
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | FileType | Ο τύπος του αρχείου. |
| pages | IPageInfo[] | Η λίστα των σελίδων προς προβολή. |
| size | Int64 | Το μέγεθος του αρχείου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Ρίχτηκε όταν*fileType* είναι μηδενικό. |
| ArgumentNullException | Ρίχτηκε όταν*pages* είναι μηδενικό. |

### Δείτε επίσης

* class [FileType](../../../groupdocs.merger.domain/filetype)
* interface [IPageInfo](../../ipageinfo)
* class [DocumentInfo](../../documentinfo)
* χώρος ονομάτων [GroupDocs.Merger.Domain.Result](../../documentinfo)
* συνέλευση [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->