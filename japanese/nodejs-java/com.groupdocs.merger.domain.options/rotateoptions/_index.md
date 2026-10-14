---
title: "RotateOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ページ回転のためのオプションを提供します。"
type: docs
weight: 33
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

ページ回転のためのオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | 新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。 |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | 新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。 |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | 新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。 |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | 新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | 回転モード（90、180、または270度）を取得します。 |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateMode | int | Mode の回転モード (\\#getMode.getMode/\\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateMode | int | Mode の回転モード (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| pageNumbers | int[] | ページ番号です。 |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateMode | int | Mode の回転モード (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


新しい [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rotateMode | int | Mode の回転モード (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### getMode() {#getMode--}
```
public final int getMode()
```


回転モード（90、180、または270度）を取得します。

**Returns:**
int
