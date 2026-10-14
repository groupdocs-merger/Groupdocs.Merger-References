---
title: "SplitOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメントのページ分割のためのオプションを提供します。"
type: docs
weight: 36
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

ドキュメントのページ分割のためのオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | 新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | ページ分割のモードを取得します。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 分割オプションを検証します。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | インデックスで分割されたドキュメントの完全なファイルパスを、事前定義された拡張子で取得します。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 出力ページプレビュー ストリームを作成または解放するための SplitStreamFactory。 |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumbers | int[] | ページ番号です。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式は、例として 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}' のように、すでに事前定義された拡張子が付いています。 |
| pageNumbers | int[] | ページ番号です。 |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式は、例として 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}' のように、すでに事前定義された拡張子が付いています。 |
| pageNumbers | int[] | ページ番号です。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式は、例として 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}' のように、すでに事前定義された拡張子が付いています。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式は、例として 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}' のように、すでに事前定義された拡張子が付いています。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式は、例として 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}' のように、すでに事前定義された拡張子が付いています。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | java.lang.Integer | 範囲モードです。 |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイルパス形式は、例として 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}' のように、すでに事前定義された拡張子が付いています。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| pageNumbers | int[] | ページ番号です。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| pageNumbers | int[] | ページ番号です。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | java.lang.Integer | 範囲モードです。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


新しい [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| splitMode | int | 分割モードは Mode (\\#getMode.getMode/\\#setMode(int).setMode(int)) です。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### getMode() {#getMode--}
```
public final int getMode()
```


ページ分割のモードを取得します。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


分割オプションを検証します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | クラス [FileType](../../com.groupdocs.merger.domain/filetype) のファイルタイプ。 |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


インデックスで分割されたドキュメントの完全なファイルパスを、事前定義された拡張子で取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int | 分割されたドキュメントのインデックス。 |
| 拡張子 | java.lang.String | ファイルの拡張子。 |

**Returns:**
java.lang.String - 完全なファイルパス。
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


出力ページプレビュー ストリームを作成または解放するための SplitStreamFactory。

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
