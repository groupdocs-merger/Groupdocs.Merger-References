---
title: "JoinOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメント結合用オプションを提供します。"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/joinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions)
```
public class JoinOptions implements IJoinOptions
```

ドキュメント結合用オプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [JoinOptions()](#JoinOptions--) | 新しい [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) クラスのインスタンスを初期化します。 |
| [JoinOptions(FileType fileType)](#JoinOptions-com.groupdocs.merger.domain.FileType-) | 新しい [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 結合するファイルのタイプです。 |
### JoinOptions() {#JoinOptions--}
```
public JoinOptions()
```


新しい [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) クラスのインスタンスを初期化します。

### JoinOptions(FileType fileType) {#JoinOptions-com.groupdocs.merger.domain.FileType-}
```
public JoinOptions(FileType fileType)
```


新しい [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |

### getType() {#getType--}
```
public final FileType getType()
```


結合するファイルのタイプです。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
