---
title: LoadOptions
second_title: Справочник по API GroupDocs.Merge для .NET
description: Инициализирует новый экземплярLoadOptionsgroupdocs.merger.domain.options/loadoptions класс.
type: docs
weight: 10
url: /ru/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(FileType fileType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | FileType | Тип загружаемого файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | String | Пароль для открытия защищенного паролем файла. |

### Смотрите также

* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| password | String | Пароль для открытия защищенного паролем файла. |
| encoding | Encoding | Кодировка, используемая при открытии текстовых файлов, таких как[`CSV`](../../../groupdocs.merger.domain/filetype/csv) или[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*encoding* нулевой. |

### Смотрите также

* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(FileType fileType, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | FileType | Тип загружаемого файла. |
| password | String | Пароль для открытия защищенного паролем файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileType | FileType | Тип загружаемого файла. |
| password | String | Пароль для открытия защищенного паролем файла. |
| encoding | Encoding | Кодировка, используемая при открытии текстовых файлов, таких как[`CSV`](../../../groupdocs.merger.domain/filetype/csv) или[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |
| ArgumentNullException | Брошен, когда*encoding* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extension | String | Расширение загружаемого файла. |
| fileType | FileType | Тип загружаемого файла. |
| password | String | Пароль для открытия защищенного паролем файла. |
| encoding | Encoding | Кодировка, используемая при открытии текстовых файлов, таких как[`CSV`](../../../groupdocs.merger.domain/filetype/csv) или[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |
| ArgumentNullException | Брошен, когда*encoding* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| iniFileType | FileType | Тип файла для инициализации. |
| fileType | FileType | Тип загружаемого файла. |
| password | String | Пароль для открытия защищенного паролем файла. |
| encoding | Encoding | Кодировка, используемая при открытии текстовых файлов, таких как[`CSV`](../../../groupdocs.merger.domain/filetype/csv) или[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*iniFileType* нулевой. |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |
| ArgumentNullException | Брошен, когда*encoding* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| iniFileType | FileType | Тип файла для инициализации. |
| fileType | FileType | Тип загружаемого файла. |
| password | String | Пароль для открытия защищенного паролем файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*iniFileType* нулевой. |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

Инициализирует новый экземпляр[`LoadOptions`](../../loadoptions) класс.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| iniFileType | FileType | Тип файла для инициализации. |
| fileType | FileType | Тип загружаемого файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*iniFileType* нулевой. |
| ArgumentNullException | Брошен, когда*fileType* нулевой. |

### Смотрите также

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* пространство имен [GroupDocs.Merger.Domain.Options](../../loadoptions)
* сборка [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
