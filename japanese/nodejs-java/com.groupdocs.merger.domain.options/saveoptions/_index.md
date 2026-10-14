---
title: "SaveOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメント保存のためのオプションを提供します。"
type: docs
weight: 34
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/saveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISaveOptions](../../com.groupdocs.merger.domain.options.interfaces/isaveoptions)
```
public class SaveOptions implements ISaveOptions
```

ドキュメント保存のためのオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SaveOptions(FileType fileType)](#SaveOptions-com.groupdocs.merger.domain.FileType-) | 新しいインスタンスの [SaveOptions](../../com.groupdocs.merger.domain.options/saveoptions) クラスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | ファイルタイプです。 |
### SaveOptions(FileType fileType) {#SaveOptions-com.groupdocs.merger.domain.FileType-}
```
public SaveOptions(FileType fileType)
```


新しいインスタンスの [SaveOptions](../../com.groupdocs.merger.domain.options/saveoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルの種類です。 |

### getType() {#getType--}
```
public final FileType getType()
```


ファイルタイプです。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
