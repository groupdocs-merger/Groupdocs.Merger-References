---
title: "DocumentInfo"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメント記述プロパティを定義します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.merger.domain.result/documentinfo/
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
| [getIndex()](#getIndex--) | ドキュメントのインデックスです。 |
| [getStream()](#getStream--) | ドキュメントストリーム。 |
| [getPassword()](#getPassword--) | ドキュメントのパスワードです。 |
| [getType()](#getType--) | ファイルタイプを取得します。 |
| [getPages()](#getPages--) | ドキュメントページのコレクションを定義します。 |
| [getPageCount()](#getPageCount--) | ドキュメントページの数です。 |
| [getSize()](#getSize--) | バイト単位のドキュメントサイズ |
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
| ストリーム | java.io.InputStream |  |
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
| ストリーム | java.io.InputStream |  |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルの種類です。 |
| パスワード | java.lang.String |  |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 表示するページのリストです。 |
| size | long | ファイルのサイズです。 |

### DocumentInfo(FileType fileType, IPageInfo[] pages, long size) {#DocumentInfo-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.result.IPageInfo---long-}
```
public DocumentInfo(FileType fileType, IPageInfo[] pages, long size)
```


新しい [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルの種類です。 |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | 表示するページのリストです。 |
| size | long | ファイルのサイズです。 |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


ドキュメントのインデックスです。

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


ドキュメントのパスワードです。

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


ドキュメントページの数です。

**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


バイト単位のドキュメントサイズ

**Returns:**
long
### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。

**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列です。
