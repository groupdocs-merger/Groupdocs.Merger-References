---
title: "ExtractOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメントのページ抽出用オプションを提供します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/extractoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions)
```
public class ExtractOptions extends PageOptions implements IExtractOptions
```

ドキュメントのページ抽出用オプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExtractOptions()](#ExtractOptions--) | 新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。 |
| [ExtractOptions(int[] pageNumbers)](#ExtractOptions-int---) | 新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。 |
| [ExtractOptions(int startNumber, int endNumber)](#ExtractOptions-int-int-) | 新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。 |
| [ExtractOptions(int startNumber, int endNumber, int mode)](#ExtractOptions-int-int-int-) | 新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。 |
### ExtractOptions() {#ExtractOptions--}
```
public ExtractOptions()
```


新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。

### ExtractOptions(int[] pageNumbers) {#ExtractOptions-int---}
```
public ExtractOptions(int[] pageNumbers)
```


新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumbers | int[] | ページ番号です。 |

### ExtractOptions(int startNumber, int endNumber) {#ExtractOptions-int-int-}
```
public ExtractOptions(int startNumber, int endNumber)
```


新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### ExtractOptions(int startNumber, int endNumber, int mode) {#ExtractOptions-int-int-int-}
```
public ExtractOptions(int startNumber, int endNumber, int mode)
```


新しいインスタンスの [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

