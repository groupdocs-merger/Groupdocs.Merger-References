---
title: "OrientationOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ページの向きに関するオプションを提供します。"
type: docs
weight: 23
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

ページの向きに関するオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | 新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。 |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | 新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。 |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | 新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。 |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | 新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | ページの向きのモードを取得します。 |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |
| pageNumbers | int[] | ページ番号です。 |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


新しいインスタンスの [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### getMode() {#getMode--}
```
public final int getMode()
```


ページの向きのモードを取得します。

**Returns:**
int
