---
title: "RemoveOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ページ削除のためのオプションを提供します。"
type: docs
weight: 31
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/removeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions)
```
public class RemoveOptions extends PageOptions implements IRemoveOptions
```

ページ削除のためのオプションを提供します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RemoveOptions()](#RemoveOptions--) | 新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。 |
| [RemoveOptions(int[] pageNumbers)](#RemoveOptions-int---) | 新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。 |
| [RemoveOptions(int startNumber, int endNumber)](#RemoveOptions-int-int-) | 新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。 |
| [RemoveOptions(int startNumber, int endNumber, int mode)](#RemoveOptions-int-int-int-) | 新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。 |
### RemoveOptions() {#RemoveOptions--}
```
public RemoveOptions()
```


新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。

### RemoveOptions(int[] pageNumbers) {#RemoveOptions-int---}
```
public RemoveOptions(int[] pageNumbers)
```


新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumbers | int[] | ページ番号です。 |

### RemoveOptions(int startNumber, int endNumber) {#RemoveOptions-int-int-}
```
public RemoveOptions(int startNumber, int endNumber)
```


新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### RemoveOptions(int startNumber, int endNumber, int mode) {#RemoveOptions-int-int-int-}
```
public RemoveOptions(int startNumber, int endNumber, int mode)
```


新しい [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

