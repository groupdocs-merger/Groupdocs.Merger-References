---
title: Merger
second_title: Справочник по API GroupDocs.Merge для .NET
description: Представляет основной класс управляющий процессом слияния документов.
type: docs
weight: 790
url: /ru/net/groupdocs.merger/merger/
---
## Merger class

Представляет основной класс, управляющий процессом слияния документов.

```csharp
public class Merger : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_4)(Stream) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_8)(string) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Инициализирует новый экземпляр[`Merger`](../merger) класс. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Защищает документ паролем. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Применяет новый режим ориентации для указанных страниц. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Удаляет ресурсы. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Создает новый документ с некоторыми страницами исходного документа. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Генерирует предварительный просмотр страниц документа. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Получает информацию о страницах документа: их размеры, максимальная высота страницы, ширина страницы с максимальной высотой. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Импортирует документ как вложение или встроенный через Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Проверяет, защищен ли документ паролем. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Объединяет документы в один документ. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Объединяет документы в один документ. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Объединяет документы в один документ. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Объединяет документы в один документ. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Объединяет документы в один документ. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Объединяет документы в один документ. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Перемещает страницу на новую позицию в документе известного формата. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Удаляет страницы из документа известного формата. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Удаляет пароль из документа. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Повернуть страницы документа. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Сохраняет результирующий документ в поток*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Сохраняет файл документа результата в*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Сохраняет файл документа результата в*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Разбивает один документ на несколько документов. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Разбивает один документ на несколько документов. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Меняет местами две страницы в документе известного формата. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Обновляет существующий пароль для документа. |

### Смотрите также

* пространство имен [GroupDocs.Merger](../../groupdocs.merger)
* сборка [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
