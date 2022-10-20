---
title: PreviewOptions
second_title: Справочник по API GroupDocs.Merge для .NET
description: Инициализирует новый экземплярPreviewOptionsgroupdocs.merger.domain.options/previewoptions класс.
type: docs
weight: 10
url: /ru/net/groupdocs.merger.domain.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, PreviewMode) {#constructor_4}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int[]) {#constructor_7}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |
| pageNumbers | Int32[] | Номера страниц. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int) {#constructor_5}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, PreviewMode, int, int, RangeMode) {#constructor_6}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, PreviewMode previewMode, int startNumber, 
    int endNumber, RangeMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |
| mode | RangeMode | Режим диапазона. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode) {#constructor}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| releasePageStream | ReleasePageStream | Метод, который выпускает поток, созданный методом createPageStream. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int[]) {#constructor_3}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| releasePageStream | ReleasePageStream | Метод, который выпускает поток, созданный методом createPageStream. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |
| pageNumbers | Int32[] | Номера страниц. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int) {#constructor_1}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| releasePageStream | ReleasePageStream | Метод, который выпускает поток, созданный методом createPageStream. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, PreviewMode, int, int, RangeMode) {#constructor_2}

Инициализирует новый экземпляр[`PreviewOptions`](../../previewoptions) класс.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    PreviewMode previewMode, int startNumber, int endNumber, RangeMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Метод, создающий экземпляр потока, используемый для записи выходных данных страницы. |
| releasePageStream | ReleasePageStream | Метод, который выпускает поток, созданный методом createPageStream. |
| previewMode | PreviewMode | Режим предварительного просмотра[`Mode`](../mode) |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |
| mode | RangeMode | Режим диапазона. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.merger.domain.common/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.merger.domain.common/releasepagestream)
* enum [PreviewMode](../../previewmode)
* enum [RangeMode](../../rangemode)
* class [PreviewOptions](../../previewoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../previewoptions)
* сборка [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
