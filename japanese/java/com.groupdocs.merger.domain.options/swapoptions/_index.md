---
title: "SwapOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ドキュメントページの入れ替えのためのオプションを提供します。"
type: docs
weight: 39
url: /ja/java/com.groupdocs.merger.domain.options/swapoptions/
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
| [SwapOptions(int firstPageNumber, int secondPageNumber)](#SwapOptions-int-int-) | 新しいインスタンスを初期化します [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFirstPageNumber()](#getFirstPageNumber--) | 交換する最初のページ番号です。 |
| [getSecondPageNumber()](#getSecondPageNumber--) | 交換する2番目のページ番号です。 |
### SwapOptions(int firstPageNumber, int secondPageNumber) {#SwapOptions-int-int-}
```
public SwapOptions(int firstPageNumber, int secondPageNumber)
```


新しいインスタンスを初期化します [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstPageNumber | int | 最初のページ番号です。 |
| secondPageNumber | int | 2番目のページ番号です。 |

### getFirstPageNumber() {#getFirstPageNumber--}
```
public final int getFirstPageNumber()
```


交換する最初のページ番号です。

**Returns:**
int
### getSecondPageNumber() {#getSecondPageNumber--}
```
public final int getSecondPageNumber()
```


交換する2番目のページ番号です。

**Returns:**
int
