---
title: LoadOptions
second_title: GroupDocs.Merger for .NET API 参考
description: 初始化新实例LoadOptionsgroupdocs.merger.domain.options/loadoptions类.
type: docs
weight: 10
url: /zh/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(FileType fileType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 要加载的文件的类型。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*fileType*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(string password)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 打开受密码保护的文件的密码。 |

### 也可以看看

* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件时使用的编码，例如[`CSV`](../../../groupdocs.merger.domain/filetype/csv)或者[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*encoding*一片空白。 |

### 也可以看看

* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(FileType fileType, string password)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 要加载的文件的类型。 |
| password | String | 打开受密码保护的文件的密码。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*fileType*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 要加载的文件的类型。 |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件时使用的编码，例如[`CSV`](../../../groupdocs.merger.domain/filetype/csv)或者[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*fileType*一片空白。 |
| ArgumentNullException | 抛出时*encoding*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| extension | String | 要加载的文件的扩展名。 |
| fileType | FileType | 要加载的文件的类型。 |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件时使用的编码，例如[`CSV`](../../../groupdocs.merger.domain/filetype/csv)或者[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*fileType*一片空白。 |
| ArgumentNullException | 抛出时*encoding*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | FileType | 要初始化的文件类型。 |
| fileType | FileType | 要加载的文件的类型。 |
| password | String | 打开受密码保护的文件的密码。 |
| encoding | Encoding | 打开基于文本的文件时使用的编码，例如[`CSV`](../../../groupdocs.merger.domain/filetype/csv)或者[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*iniFileType*一片空白。 |
| ArgumentNullException | 抛出时*fileType*一片空白。 |
| ArgumentNullException | 抛出时*encoding*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | FileType | 要初始化的文件类型。 |
| fileType | FileType | 要加载的文件的类型。 |
| password | String | 打开受密码保护的文件的密码。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*iniFileType*一片空白。 |
| ArgumentNullException | 抛出时*fileType*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

初始化新实例[`LoadOptions`](../../loadoptions)类.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| iniFileType | FileType | 要初始化的文件类型。 |
| fileType | FileType | 要加载的文件的类型。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*iniFileType*一片空白。 |
| ArgumentNullException | 抛出时*fileType*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 命名空间 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 部件 [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
