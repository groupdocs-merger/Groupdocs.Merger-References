---
title: "OrientationOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ページの向き用オプションを提供します。"
type: docs
weight: 23
url: /ja/java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

ページの向き用オプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | 新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。 |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | 新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。 |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | 新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。 |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | 新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMode()](#getMode--) | ページの向きのモードを取得します。 |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |
| pageNumbers | int[] | ページ番号です。 |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号。 |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


新しいインスタンスを初期化します [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) の向きモードです。 |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号。 |
| モード | int | 範囲モード。 |

### getMode() {#getMode--}
```
public final int getMode()
```


ページの向きのモードを取得します。

**Returns:**
int
