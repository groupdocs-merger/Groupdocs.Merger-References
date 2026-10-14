---
title: "ITextSplitOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "テキスト分割オプション用のインターフェイス。"
type: docs
weight: 35
url: /ja/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

テキスト分割オプション用のインターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | テキスト分割用の行番号です。 |
| [getMode()](#getMode--) | テキスト分割のモードです。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 分割オプションを検証します。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | インデックスで指定された拡張子を使用して、分割されたドキュメントの完全なファイルパスを取得します。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 出力分割ストリームを作成するメソッドを定義するデリゲート。 |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


テキスト分割用の行番号です。

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


テキスト分割のモードです。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


分割オプションを検証します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | クラス [FileType](../../com.groupdocs.merger.domain/filetype) のファイルタイプ。 |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


出力分割ストリームを作成するメソッドを定義するデリゲート。

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
