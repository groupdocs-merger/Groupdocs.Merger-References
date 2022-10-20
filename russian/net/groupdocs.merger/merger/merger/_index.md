---
title: Merger
second_title: Справочник по API GroupDocs.Merge для .NET
description: Инициализирует новый экземплярMergergroupdocs.merger/merger класс.
type: docs
weight: 10
url: /ru/net/groupdocs.merger/merger/merger/
---
## Merger(Stream) {#constructor_4}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Читаемый поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*document* нулевой. |

### Смотрите также

* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions) {#constructor_5}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Stream document, ILoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Читаемый поток. |
| loadOptions | ILoadOptions | Параметры загрузки документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*document* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |

### Смотрите также

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Stream, MergerSettings) {#constructor_7}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Stream document, MergerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Читаемый поток. |
| settings | MergerSettings | Настройки слияния. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*document* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Смотрите также

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Stream, ILoadOptions, MergerSettings) {#constructor_6}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Stream document, ILoadOptions loadOptions, MergerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Читаемый поток. |
| loadOptions | ILoadOptions | Параметры загрузки документа. |
| settings | MergerSettings | Настройки слияния. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*document* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Смотрите также

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;) {#constructor}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Func<Stream> getFileStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |

### Смотрите также

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions) {#constructor_1}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | ILoadOptions | Параметры загрузки документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |

### Смотрите также

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, MergerSettings) {#constructor_3}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Func<Stream> getFileStream, MergerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |
| settings | MergerSettings | Настройки слияния. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Смотрите также

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) {#constructor_2}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(Func<Stream> getFileStream, ILoadOptions loadOptions, MergerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |
| loadOptions | ILoadOptions | Параметры загрузки документа. |
| settings | MergerSettings | Настройки слияния. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Смотрите также

* delegate [Func&lt;TResult&gt;](../../../groupdocs.merger.domain.common/func-1)
* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(string) {#constructor_8}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*filePath* является нулевым или пустым. |

### Смотрите также

* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions) {#constructor_9}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(string filePath, ILoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| loadOptions | ILoadOptions | Параметры загрузки документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*filePath* является нулевым или пустым. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |

### Смотрите также

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(string, MergerSettings) {#constructor_11}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(string filePath, MergerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| settings | MergerSettings | Настройки слияния. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*filePath* является нулевым или пустым. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Смотрите также

* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

---

## Merger(string, ILoadOptions, MergerSettings) {#constructor_10}

Инициализирует новый экземпляр[`Merger`](../../merger) класс.

```csharp
public Merger(string filePath, ILoadOptions loadOptions, MergerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| loadOptions | ILoadOptions | Параметры загрузки документа. |
| settings | MergerSettings | Настройки слияния. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*filePath* является нулевым или пустым. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Смотрите также

* interface [ILoadOptions](../../../groupdocs.merger.domain.options/iloadoptions)
* class [MergerSettings](../../mergersettings)
* class [Merger](../../merger)
* пространство имен [GroupDocs.Merger](../../merger)
* сборка [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
