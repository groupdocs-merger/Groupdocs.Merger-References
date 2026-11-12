---
title: "LoadOptions"
second_title: "GroupDocs.Merger for .NET API 参考"
description: "初始化 LoadOptionsgroupdocs.merger.domain.options/loadoptions 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(FileType fileType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 要加载的文件类型。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 打开受密码保护的文件的密码。 |

### 另见

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(string password, Encoding encoding)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件（例如 [`CSV`](../../../groupdocs.merger.domain/filetype/csv) 或 [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）时使用的编码。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *encoding* 为 null 时抛出。 |

### 另见

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(FileType fileType, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 要加载的文件类型。 |
| password | String | 打开受密码保护的文件的密码。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 要加载的文件类型。 |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件（例如 [`CSV`](../../../groupdocs.merger.domain/filetype/csv) 或 [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）时使用的编码。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |
| ArgumentNullException | 当 *encoding* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| extension | String | 要加载的文件的扩展名。 |
| fileType | FileType | 要加载的文件类型。 |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件（例如 [`CSV`](../../../groupdocs.merger.domain/filetype/csv) 或 [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）时使用的编码。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |
| ArgumentNullException | 当 *encoding* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | FileType | 要初始化的文件类型。 |
| fileType | FileType | 要加载的文件类型。 |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件（例如 [`CSV`](../../../groupdocs.merger.domain/filetype/csv) 或 [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）时使用的编码。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *iniFileType* 为 null 时抛出。 |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |
| ArgumentNullException | 当 *encoding* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | FileType | 要初始化的文件类型。 |
| fileType | FileType | 要加载的文件类型。 |
| password | String | 打开受密码保护的文件的密码。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *iniFileType* 为 null 时抛出。 |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

初始化 [`LoadOptions`](../../loadoptions) 类的新实例。

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | FileType | 要初始化的文件类型。 |
| fileType | FileType | 要加载的文件类型。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *iniFileType* 为 null 时抛出。 |
| ArgumentNullException | 当 *fileType* 为 null 时抛出。 |

### 另见

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
