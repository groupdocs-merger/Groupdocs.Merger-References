---
title: "LoadOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ドキュメント読み込み用オプションを提供します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.merger.domain.options/loadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

ドキュメント読み込み用オプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(String password)](#LoadOptions-java.lang.String-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(String password, Charset encoding)](#LoadOptions-java.lang.String-java.nio.charset.Charset-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(String extension, FileType fileType, String password, Charset encoding)](#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(FileType iniFileType, FileType fileType, String password)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
| [LoadOptions(FileType iniFileType, FileType fileType)](#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | 新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | ロードするファイルのタイプ。 |
| [getExtension()](#getExtension--) | 初期化するファイルの拡張子です。 |
| [getPassword()](#getPassword--) | パスワードで保護されたファイルを開くためのパスワード。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。 |
### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType fileType)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |

### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |

### LoadOptions(String password, Charset encoding) {#LoadOptions-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String password, Charset encoding)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | java.nio.charset.Charset | テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。 |

### LoadOptions(FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType fileType, String password)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |

### LoadOptions(FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType fileType, String password, Charset encoding)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | java.nio.charset.Charset | テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。 |

### LoadOptions(String extension, FileType fileType, String password, Charset encoding) {#LoadOptions-java.lang.String-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(String extension, FileType fileType, String password, Charset encoding)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 拡張子 | java.lang.String | 読み込むファイルの拡張子です。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | java.nio.charset.Charset | テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。 |

### LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-java.nio.charset.Charset-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password, Charset encoding)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 初期化するファイルのタイプです。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |
| encoding | java.nio.charset.Charset | テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディング。 |

### LoadOptions(FileType iniFileType, FileType fileType, String password) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public LoadOptions(FileType iniFileType, FileType fileType, String password)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 初期化するファイルのタイプです。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |
| パスワード | java.lang.String | パスワードで保護されたファイルを開くためのパスワード。 |

### LoadOptions(FileType iniFileType, FileType fileType) {#LoadOptions-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public LoadOptions(FileType iniFileType, FileType fileType)
```


新しい [LoadOptions](../../com.groupdocs.merger.domain.options/loadoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| iniFileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 初期化するファイルのタイプです。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ロードするファイルのタイプ。 |

### getType() {#getType--}
```
public final FileType getType()
```


ロードするファイルのタイプ。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getExtension() {#getExtension--}
```
public final String getExtension()
```


初期化するファイルの拡張子です。

**Returns:**
java.lang.String
### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワードで保護されたファイルを開くためのパスワード。

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


テキストベースのファイル（例: [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) または [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT)）を開く際に使用されるエンコーディングです。デフォルト値は System.Text.Encoding.Default (java.nio.charset.Charset) です。

**Returns:**
java.nio.charset.Charset
