---
title: "WordJoinOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "Word 結合オプションです。"
type: docs
weight: 43
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Word 結合オプションです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | Word の結合モードです。 |
| [setMode(int value)](#setMode-int-) | Word の結合モードです。 |
| [getCompliance()](#getCompliance--) | Word Ooxml フォーマットのコンプライアンスモード |
| [setCompliance(int value)](#setCompliance-int-) | Word Ooxml フォーマットのコンプライアンスモード |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumbers | int[] | ページ番号です。 |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| pageNumbers | int[] | ページ番号です。 |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


新しいインスタンスの [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### getMode() {#getMode--}
```
public final int getMode()
```


Word の結合モードです。

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Word の結合モードです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Word Ooxml フォーマットのコンプライアンスモード

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Word Ooxml フォーマットのコンプライアンスモード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

