---
title: "WordJoinOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "Word結合オプションです。"
type: docs
weight: 45
url: /ja/java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Word結合オプションです。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | Word 結合モード。 |
| [setMode(int value)](#setMode-int-) | Word 結合モード。 |
| [getCompliance()](#getCompliance--) | Word Ooxml 形式のコンプライアンスモード |
| [setCompliance(int value)](#setCompliance-int-) | Word Ooxml 形式のコンプライアンスモード |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumbers | int[] | ページ番号です。 |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号。 |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号。 |
| モード | int | 範囲モード。 |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| pageNumbers | int[] | ページ番号です。 |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号。 |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


新しい [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 結合するファイルのタイプです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号。 |
| モード | int | 範囲モード。 |

### getMode() {#getMode--}
```
public final int getMode()
```


Word 結合モード。

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Word 結合モード。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Word Ooxml 形式のコンプライアンスモード

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Word Ooxml 形式のコンプライアンスモード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

