---
title: SplitOptions
second_title: Справочник по API GroupDocs.Merge для .NET
description: Инициализирует новый экземплярSplitOptionsgroupdocs.merger.domain.options/splitoptions класс.
type: docs
weight: 10
url: /ru/net/groupdocs.merger.domain.options/splitoptions/splitoptions/
---
## SplitOptions(string, int[]) {#constructor_12}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например «c:/split{0}.doc» или «c:/split{0}.{1}» с уже заданным расширением. |
| pageNumbers | Int32[] | Номера страниц. |

### Смотрите также

* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int[], SplitMode) {#constructor_13}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(string filePathFormat, int[] pageNumbers, SplitMode splitMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например «c:/split{0}.doc» или «c:/split{0}.{1}» с уже заданным расширением. |
| pageNumbers | Int32[] | Номера страниц. |
| splitMode | SplitMode | Режим разделения[`Mode`](../mode). |

### Смотрите также

* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int) {#constructor_10}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например «c:/split{0}.doc» или «c:/split{0}.{1}» с уже заданным расширением. |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |

### Смотрите также

* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(string, int, int, RangeMode) {#constructor_11}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(string filePathFormat, int startNumber, int endNumber, RangeMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например «c:/split{0}.doc» или «c:/split{0}.{1}» с уже заданным расширением. |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |
| mode | RangeMode | Режим диапазона. |

### Смотрите также

* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream) {#constructor}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[]) {#constructor_8}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| pageNumbers | Int32[] | Номера страниц. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int[], SplitMode) {#constructor_9}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int[] pageNumbers, SplitMode splitMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| pageNumbers | Int32[] | Номера страниц. |
| splitMode | SplitMode | Режим разделения[`Mode`](../mode). |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int) {#constructor_6}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, int, int, RangeMode) {#constructor_7}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, int startNumber, int endNumber, 
    RangeMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |
| mode | RangeMode | Режим диапазона. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream) {#constructor_1}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_4}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |
| pageNumbers | Int32[] | Номера страниц. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int[], SplitMode) {#constructor_5}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] pageNumbers, SplitMode splitMode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |
| pageNumbers | Int32[] | Номера страниц. |
| splitMode | SplitMode | Режим разделения[`Mode`](../mode). |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [SplitMode](../../splitmode)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int) {#constructor_2}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## SplitOptions(CreateSplitStream, ReleaseSplitStream, int, int, RangeMode) {#constructor_3}

Инициализирует новый экземпляр[`SplitOptions`](../../splitoptions) класс.

```csharp
public SplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int startNumber, int endNumber, RangeMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |
| startNumber | Int32 | Номер начальной страницы. |
| endNumber | Int32 | Конечный номер страницы. |
| mode | RangeMode | Режим диапазона. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [RangeMode](../../rangemode)
* class [SplitOptions](../../splitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../splitoptions)
* сборка [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
