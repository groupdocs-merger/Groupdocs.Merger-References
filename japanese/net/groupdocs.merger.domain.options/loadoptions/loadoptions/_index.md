---
title: "LoadOptions"
second_title: "GroupDocs.Merger for .NET API リファレンス"
description: "LoadOptionsgroupdocs.merger.domain.options/loadoptions クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(FileType fileType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | FileType | ロードするファイルの種類です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(string password)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |

### 関連項目

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(string password, Encoding encoding)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |
| encoding | Encoding | テキストベースのファイル（例: [`CSV`](../../../groupdocs.merger.domain/filetype/csv) や [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）を開く際に使用されるエンコーディングです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *encoding* が null のときにスローされます。 |

### 関連項目

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(FileType fileType, string password)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | FileType | ロードするファイルの種類です。 |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | FileType | ロードするファイルの種類です。 |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |
| encoding | Encoding | テキストベースのファイル（例: [`CSV`](../../../groupdocs.merger.domain/filetype/csv) や [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）を開く際に使用されるエンコーディングです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *encoding* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| extension | String | ロードするファイルの拡張子です。 |
| fileType | FileType | ロードするファイルの種類です。 |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |
| encoding | Encoding | テキストベースのファイル（例: [`CSV`](../../../groupdocs.merger.domain/filetype/csv) や [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）を開く際に使用されるエンコーディングです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *encoding* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iniFileType | FileType | 初期化するファイルのタイプです。 |
| fileType | FileType | ロードするファイルの種類です。 |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |
| encoding | Encoding | テキストベースのファイル（例: [`CSV`](../../../groupdocs.merger.domain/filetype/csv) や [`TXT`](../../../groupdocs.merger.domain/filetype/txt)）を開く際に使用されるエンコーディングです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *iniFileType* が null のときにスローされます。 |
| ArgumentNullException | *fileType* が null のときにスローされます。 |
| ArgumentNullException | *encoding* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iniFileType | FileType | 初期化するファイルのタイプです。 |
| fileType | FileType | ロードするファイルの種類です。 |
| password | String | パスワードで保護されたファイルを開くためのパスワードです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *iniFileType* が null のときにスローされます。 |
| ArgumentNullException | *fileType* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

新しいインスタンスを初期化します [`LoadOptions`](../../loadoptions) クラス。

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iniFileType | FileType | 初期化するファイルのタイプです。 |
| fileType | FileType | ロードするファイルの種類です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *iniFileType* が null のときにスローされます。 |
| ArgumentNullException | *fileType* が null のときにスローされます。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Merger.Domain.Options](../../../groupdocs.merger.domain.options)
* assembly [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
