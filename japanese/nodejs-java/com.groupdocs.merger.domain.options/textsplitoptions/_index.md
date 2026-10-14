---
title: "TextSplitOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメントテキスト分割のためのオプションを提供します。"
type: docs
weight: 39
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

ドキュメントテキスト分割のためのオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | 新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。 |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | 新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。 |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | 新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。 |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | 新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。 |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。 |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | 新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | テキスト分割のモードです。 |
| [getLineNumbers()](#getLineNumbers--) | テキスト分割用の行番号です。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 分割オプションを検証します。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | インデックスで指定された拡張子を使用して、分割されたドキュメントの完全なファイルパスを取得します。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 出力ページプレビュー ストリームを作成または解放するための SplitStreamFactory。 |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lineNumbers | int[] | テキスト分割用の行番号です。 |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | int | テキスト分割のモードです。 |
| lineNumbers | int[] | テキスト分割用の行番号です。 |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイル パスの形式（例: 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}'）で、拡張子は既に定義されています。 |
| lineNumbers | int[] | テキスト分割用の行番号です。 |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePathFormat | java.lang.String | ファイル パスの形式（例: 'c:/split\\{0\\}.doc' または 'c:/split\\{0\\}.\\{1\\}'）で、拡張子は既に定義されています。 |
| mode | int | テキスト分割のモードです。 |
| lineNumbers | int[] | テキスト分割用の行番号です。 |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| lineNumbers | int[] | テキスト分割用の行番号です。 |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


新しい [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 出力分割データを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| mode | int | テキスト分割のモードです。 |
| lineNumbers | int[] | テキスト分割用の行番号です。 |

### getMode() {#getMode--}
```
public final int getMode()
```


テキスト分割のモードです。

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


テキスト分割用の行番号です。

**Returns:**
int[]
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


インデックスで指定された拡張子を使用して、分割されたドキュメントの完全なファイルパスを取得します。

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
