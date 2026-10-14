---
title: "ImageJoinOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "画像結合オプション。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

画像結合オプション。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | 新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。 |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | 新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。 |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | 新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。 |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | 新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 画像ファイルの種類です。 |
| [getMode()](#getMode--) | 画像結合モードです。 |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 画像ファイルの種類です。 |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageJoinMode | int | 画像結合モードです。 |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


新しい [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 画像ファイルの種類です。 |
| imageJoinMode | int | 画像結合モードです。 |

### getType() {#getType--}
```
public final FileType getType()
```


画像ファイルの種類です。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


画像結合モードです。

**Returns:**
int
