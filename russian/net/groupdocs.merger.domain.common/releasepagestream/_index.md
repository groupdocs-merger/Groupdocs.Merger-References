---
title: ReleasePageStream
second_title: Справочник по API GroupDocs.Merge для .NET
description: Делегат определяющий метод выпуска потока предварительного просмотра выходной страницы.
type: docs
weight: 80
url: /ru/net/groupdocs.merger.domain.common/releasepagestream/
---
## ReleasePageStream delegate

Делегат, определяющий метод выпуска потока предварительного просмотра выходной страницы.

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream createPageStream);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы. |
| createPageStream | Stream | Поток, созданный*createPageStream* метод. |

### Смотрите также

* пространство имен [GroupDocs.Merger.Domain.Common](../../groupdocs.merger.domain.common)
* сборка [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
