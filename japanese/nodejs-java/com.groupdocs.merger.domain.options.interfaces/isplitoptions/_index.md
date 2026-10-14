---
title: "ISplitOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "分割オプション用のインターフェイス。"
type: docs
weight: 33
url: /ja/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

分割オプション用のインターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | ページ分割のモードを取得します。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 分割オプションを検証します。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | インデックスで指定された拡張子を使用して、分割されたドキュメントの完全なファイルパスを取得します。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 出力分割ストリームを作成するメソッドを定義するデリゲート。 |
### getMode() {#getMode--}
```
public abstract int getMode()
```


ページ分割のモードを取得します。

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
