---
title: "DocumentInfo"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ドキュメント記述プロパティを定義します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.merger.domain.result/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

ドキュメント記述プロパティを定義します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | 新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。 |
| [DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)](#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-) | 新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。 |
| [DocumentInfo(FileType fileType, IPageInfo[] pages, long size)](#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-) | 新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getIndex()](#getIndex--) | ドキュメントのインデックス。 |
| [getStream()](#getStream--) | ドキュメントストリーム。 |
| [getPassword()](#getPassword--) | ドキュメントのパスワード。 |
| [getType()](#getType--) | ファイルタイプを取得します。 |
| [getPages()](#getPages--) | ドキュメントページのコレクションを定義します。 |
| [getPageCount()](#getPageCount--) | ドキュメントのページ数。 |
| [getSize()](#getSize--) | ドキュメントサイズ（バイト） |
| [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
### DocumentInfo(int index, InputStream stream, FileType fileType, String password) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password)
```


新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルの種類です。 |
| パスワード | java.lang.String |  |

### DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size) {#DocumentInfo-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(int index, InputStream stream, FileType fileType, String password, IPageInfo[] pages, long size)
```


新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int |  |
| stream | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルの種類です。 |
| パスワード | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 表示するページのリスト。 |
| サイズ | long | ファイルのサイズ。 |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルの種類です。 |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 表示するページのリスト。 |
| サイズ | long | ファイルのサイズ。 |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


ドキュメントのインデックス。

**Returns:**
int
### getStream() {#getStream--}
```
public final InputStream getStream()
```


ドキュメントストリーム。

**Returns:**
java.io.InputStream
### getPassword() {#getPassword--}
```
public final String getPassword()
```


ドキュメントのパスワード。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final FileType getType()
```


ファイルタイプを取得します。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPages() {#getPages--}
```
public final IPageInfo[] getPages()
```


ドキュメントページのコレクションを定義します。

**Returns:**
com.groupdocs.merger.domain.result.IPageInfo[]
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


ドキュメントのページ数。

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


ドキュメントサイズ（バイト）

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。

**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列。
