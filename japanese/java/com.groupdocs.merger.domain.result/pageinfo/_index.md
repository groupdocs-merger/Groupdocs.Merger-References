---
title: "PageInfo"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ページ記述プロパティを定義します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

ページ記述プロパティを定義します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | 新しい [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) クラスのインスタンスを初期化します。 |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | 新しい [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDocument()](#getDocument--) | ドキュメント情報を取得します。 |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | ドキュメント情報を取得します。 |
| [getNumber()](#getNumber--) | ページ番号を取得します。 |
| [getVisible()](#getVisible--) | ページが表示されているかどうかを示します。 |
| [getWidth()](#getWidth--) | 画像に変換したときのページ幅（ピクセル）を取得します。 |
| [getHeight()](#getHeight--) | 画像に変換したときのページ高さ（ピクセル）を取得します。 |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


新しい [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| 表示中 | boolean | ページの表示状態インジケータです。 |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


新しい [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | ページ番号です。 |
| 表示中 | boolean | ページの表示状態インジケータです。 |
| 幅 | int | JPG または PNG として表示する際のページ幅（ピクセル）です。 |
| 高さ | int | JPG または PNG として表示する際のページ高さ（ピクセル）です。 |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


ドキュメント情報を取得します。

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


ドキュメント情報を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


ページ番号を取得します。

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


ページが表示されているかどうかを示します。

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


画像に変換したときのページ幅（ピクセル）を取得します。

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


画像に変換したときのページ高さ（ピクセル）を取得します。

**Returns:**
int
