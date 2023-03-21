---
title: LoadOptions
second_title: GroupDocs.Merger for .NET API リファレンス
description: の新しいインスタンスを初期化しますLoadOptionsgroupdocs.merger.domain.options/loadoptionsclass.
type: docs
weight: 10
url: /ja/net/groupdocs.merger.domain.options/loadoptions/loadoptions/
---
## LoadOptions(FileType) {#constructor}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(FileType fileType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ロードするファイルのタイプ。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(string) {#constructor_6}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(string password)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |

### 関連項目

* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(string, Encoding) {#constructor_8}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(string password, Encoding encoding)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | Encoding | などのテキストベースのファイルを開くときに使用されるエンコーディング。[`CSV`](../../../groupdocs.merger.domain/filetype/csv)また[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*encoding*無効である。 |

### 関連項目

* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string) {#constructor_4}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(FileType fileType, string password)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ロードするファイルのタイプ。 |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, string, Encoding) {#constructor_5}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(FileType fileType, string password, Encoding encoding)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fileType | FileType | ロードするファイルのタイプ。 |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | Encoding | などのテキストベースのファイルを開くときに使用されるエンコーディング。[`CSV`](../../../groupdocs.merger.domain/filetype/csv)また[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |
| ArgumentNullException | スローされるタイミング*encoding*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(string, FileType, string, Encoding) {#constructor_7}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(string extension, FileType fileType, string password, Encoding encoding)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| extension | String | ロードするファイルの拡張子。 |
| fileType | FileType | ロードするファイルのタイプ。 |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | Encoding | などのテキストベースのファイルを開くときに使用されるエンコーディング。[`CSV`](../../../groupdocs.merger.domain/filetype/csv)また[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |
| ArgumentNullException | スローされるタイミング*encoding*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string, Encoding) {#constructor_3}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password, Encoding encoding)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| iniFileType | FileType | 初期化するファイルのタイプ。 |
| fileType | FileType | ロードするファイルのタイプ。 |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | Encoding | などのテキストベースのファイルを開くときに使用されるエンコーディング。[`CSV`](../../../groupdocs.merger.domain/filetype/csv)また[`TXT`](../../../groupdocs.merger.domain/filetype/txt). |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*iniFileType*無効である。 |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |
| ArgumentNullException | スローされるタイミング*encoding*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType, string) {#constructor_2}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType, string password)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| iniFileType | FileType | 初期化するファイルのタイプ。 |
| fileType | FileType | ロードするファイルのタイプ。 |
| password | String | パスワードで保護されたファイルを開くためのパスワード。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*iniFileType*無効である。 |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

---

## LoadOptions(FileType, FileType) {#constructor_1}

の新しいインスタンスを初期化します[`LoadOptions`](../../loadoptions)class.

```csharp
public LoadOptions(FileType iniFileType, FileType fileType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| iniFileType | FileType | 初期化するファイルのタイプ。 |
| fileType | FileType | ロードするファイルのタイプ。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*iniFileType*無効である。 |
| ArgumentNullException | スローされるタイミング*fileType*無効である。 |

### 関連項目

* class [FileType](../../../groupdocs.merger.domain/filetype)
* class [LoadOptions](../../loadoptions)
* 名前空間 [GroupDocs.Merger.Domain.Options](../../loadoptions)
* 組み立て [GroupDocs.Merger](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
