---
title: "PageJoinOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメント結合用オプションを提供します。"
type: docs
weight: 25
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

ドキュメント結合用オプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getType()](#getType--) | 結合するファイルのタイプです。 |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumbers | int[] | ページ番号です。 |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| pageNumbers | int[] | ページ番号です。 |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


新しい [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### getType() {#getType--}
```
public final FileType getType()
```


結合するファイルのタイプです。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
