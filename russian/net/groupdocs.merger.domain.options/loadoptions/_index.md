---
title: LoadOptions
second_title: Справочник по API GroupDocs.Merge для .NET
description: Предоставляет параметры загрузки документа.
type: docs
weight: 420
url: /ru/net/groupdocs.merger.domain.options/loadoptions/
---
## LoadOptions class

Предоставляет параметры загрузки документа.

```csharp
public class LoadOptions : ILoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LoadOptions](loadoptions#constructor)(FileType) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_6)(string) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_1)(FileType, FileType) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_4)(FileType, string) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_8)(string, Encoding) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_2)(FileType, FileType, string) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_5)(FileType, string, Encoding) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_3)(FileType, FileType, string, Encoding) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |
| [LoadOptions](loadoptions#constructor_7)(string, FileType, string, Encoding) | Инициализирует новый экземпляр[`LoadOptions`](../loadoptions) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Encoding](../../groupdocs.merger.domain.options/loadoptions/encoding) { get; } | Кодировка, используемая при открытии текстовых файлов, таких как[`CSV`](../../groupdocs.merger.domain/filetype/csv) или[`TXT`](../../groupdocs.merger.domain/filetype/txt) . Значение по умолчанию:Default . |
| [Extension](../../groupdocs.merger.domain.options/loadoptions/extension) { get; } | Расширение файла для инициализации. |
| [Password](../../groupdocs.merger.domain.options/loadoptions/password) { get; } | Пароль для открытия защищенного паролем файла. |
| [Type](../../groupdocs.merger.domain.options/loadoptions/type) { get; } | Тип загружаемого файла. |

### Смотрите также

* interface [ILoadOptions](../iloadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../groupdocs.merger.domain.options)
* сборка [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
