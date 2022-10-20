---
title: TextSplitOptions
second_title: Справочник по API GroupDocs.Merge для .NET
description: Инициализирует новый экземплярTextSplitOptionsgroupdocs.merger.domain.options/textsplitoptions класс.
type: docs
weight: 10
url: /ru/net/groupdocs.merger.domain.options/textsplitoptions/textsplitoptions/
---
## TextSplitOptions(string, int[]) {#constructor_5}

Инициализирует новый экземпляр[`TextSplitOptions`](../../textsplitoptions) класс.

```csharp
public TextSplitOptions(string filePathFormat, int[] lineNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например 'c:/split{0}.doc' или 'c:/split{0}.{1}' с уже определенным расширением. |
| lineNumbers | Int32[] | Номера строк для разделения текста. |

### Смотрите также

* class [TextSplitOptions](../../textsplitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## TextSplitOptions(string, TextSplitMode, int[]) {#constructor_4}

Инициализирует новый экземпляр[`TextSplitOptions`](../../textsplitoptions) класс.

```csharp
public TextSplitOptions(string filePathFormat, TextSplitMode mode, int[] lineNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePathFormat | String | Формат пути к файлу, например 'c:/split{0}.doc' или 'c:/split{0}.{1}' с уже определенным расширением. |
| mode | TextSplitMode | Режим разделения текста. |
| lineNumbers | Int32[] | Номера строк для разделения текста. |

### Смотрите также

* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, int[]) {#constructor_3}

Инициализирует новый экземпляр[`TextSplitOptions`](../../textsplitoptions) класс.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, int[] lineNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| lineNumbers | Int32[] | Номера строк для разделения текста. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, TextSplitMode, int[]) {#constructor_2}

Инициализирует новый экземпляр[`TextSplitOptions`](../../textsplitoptions) класс.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, TextSplitMode mode, int[] lineNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| mode | TextSplitMode | Режим разделения текста. |
| lineNumbers | Int32[] | Номера строк для разделения текста. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, int[]) {#constructor_1}

Инициализирует новый экземпляр[`TextSplitOptions`](../../textsplitoptions) класс.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    int[] lineNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |
| lineNumbers | Int32[] | Номера строк для разделения текста. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* class [TextSplitOptions](../../textsplitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* сборка [GroupDocs.Merger](../../../)

---

## TextSplitOptions(CreateSplitStream, ReleaseSplitStream, TextSplitMode, int[]) {#constructor}

Инициализирует новый экземпляр[`TextSplitOptions`](../../textsplitoptions) класс.

```csharp
public TextSplitOptions(CreateSplitStream createSplitStream, ReleaseSplitStream releaseSplitStream, 
    TextSplitMode mode, int[] lineNumbers)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createSplitStream | CreateSplitStream | Метод, создающий экземпляр потока, используемый для записи выходных разделенных данных. |
| releaseSplitStream | ReleaseSplitStream | Метод, который выпускает поток, созданный методом createPageStream. |
| mode | TextSplitMode | Режим разделения текста. |
| lineNumbers | Int32[] | Номера строк для разделения текста. |

### Смотрите также

* delegate [CreateSplitStream](../../../groupdocs.merger.domain.common/createsplitstream)
* delegate [ReleaseSplitStream](../../../groupdocs.merger.domain.common/releasesplitstream)
* enum [TextSplitMode](../../textsplitmode)
* class [TextSplitOptions](../../textsplitoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../textsplitoptions)
* сборка [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
