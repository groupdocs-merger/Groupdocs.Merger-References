---
title: "SwapOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメントページの入れ替えのためのオプションを提供します。"
type: docs
weight: 37
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/swapoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions)
```
public class SwapOptions implements ISwapOptions
```

ドキュメントページの入れ替えのためのオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SwapOptions(int firstPageNumber, int secondPageNumber)](#SwapOptions-int-int-) | 新しい [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFirstPageNumber()](#getFirstPageNumber--) | 交換する最初のページ番号。 |
| [getSecondPageNumber()](#getSecondPageNumber--) | 交換する2番目のページ番号。 |
### SwapOptions(int firstPageNumber, int secondPageNumber) {#SwapOptions-int-int-}
```
public SwapOptions(int firstPageNumber, int secondPageNumber)
```


新しい [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstPageNumber | int | 最初のページ番号です。 |
| secondPageNumber | int | 2番目のページ番号です。 |

### getFirstPageNumber() {#getFirstPageNumber--}
```
public final int getFirstPageNumber()
```


交換する最初のページ番号。

**Returns:**
int
### getSecondPageNumber() {#getSecondPageNumber--}
```
public final int getSecondPageNumber()
```


交換する2番目のページ番号。

**Returns:**
int
