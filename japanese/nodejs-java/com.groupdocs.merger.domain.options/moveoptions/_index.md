---
title: "MoveOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメントページの移動用オプションを提供します。"
type: docs
weight: 17
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

ドキュメントページの移動用オプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | 新しい [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | 移動するページ番号を取得または設定します。 |
| [getNewPageNumber()](#getNewPageNumber--) | 新しいページ番号を取得または設定します。 |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


新しい [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumberToMove | int | 移動するページ番号です。 |
| newPageNumber | int | 新しいページ番号です。 |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


移動するページ番号を取得または設定します。

値: 移動するページ番号です。

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


新しいページ番号を取得または設定します。

値: 新しいページ番号です。

**Returns:**
int
