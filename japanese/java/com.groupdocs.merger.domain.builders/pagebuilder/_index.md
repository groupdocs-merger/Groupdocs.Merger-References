---
title: "PageBuilder"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "ドキュメントからページコレクションを取得するための PageInfo ビルダー。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.merger.domain.builders/pagebuilder/
---
**Inheritance:**
java.lang.Object
```
public class PageBuilder
```

ドキュメントからページコレクションを取得するための PageInfo ビルダー。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PageBuilder()](#PageBuilder--) | 新しいインスタンスを初期化します [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) クラスです。 |
| [PageBuilder(PageBuilderOptions options)](#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | 新しいインスタンスを初期化します [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) クラスです。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOptions()](#getOptions--) | ページビルダーのオプションです。 |
| [getPages()](#getPages--) | ページコレクションです。 |
| [getDocuments()](#getDocuments--) | ドキュメントコレクションです。 |
| [addDocument(int index, InputStream stream, FileType fileType, String password)](#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-) | ドキュメントをドキュメントコレクションに追加します。 |
| [addDocument(DocumentInfo document)](#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | ドキュメントをドキュメントコレクションに追加します。 |
| [addPage(int documentIndex, int pageNumber)](#addPage-int-int-) | ページをページコレクションに追加します。 |
| [addPage(IPageInfo page)](#addPage-com.groupdocs.merger.domain.result.IPageInfo-) | ページをページコレクションに追加します。 |
| [addPageRange(IPageInfo[] pages)](#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---) | ページをページコレクションに追加します。 |
| [clear()](#clear--) | 内部コレクションをクリアします。 |
### PageBuilder() {#PageBuilder--}
```
public PageBuilder()
```


新しいインスタンスを初期化します [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) クラスです。

### PageBuilder(PageBuilderOptions options) {#PageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public PageBuilder(PageBuilderOptions options)
```


新しいインスタンスを初期化します [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) クラスです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) | ページビルダーのオプションです。 |

### getOptions() {#getOptions--}
```
public final PageBuilderOptions getOptions()
```


ページビルダーのオプションです。

**Returns:**
[PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions)
### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


ページコレクションです。

**Returns:**
java.util.List<com.groupdocs.merger.domain.result.PageInfo>
### getDocuments() {#getDocuments--}
```
public final Map<Integer,DocumentInfo> getDocuments()
```


ドキュメントコレクションです。

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.merger.domain.result.DocumentInfo>
### addDocument(int index, InputStream stream, FileType fileType, String password) {#addDocument-int-java.io.InputStream-com.groupdocs.merger.domain.FileType-java.lang.String-}
```
public final void addDocument(int index, InputStream stream, FileType fileType, String password)
```


ドキュメントをドキュメントコレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス | int | DocumentInfo のインデックスです。 |
| stream | java.io.InputStream | DocumentInfo のストリームです。 |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | DocumentInfo の型です。 |
| パスワード | java.lang.String | DocumentInfo のパスワードです。 |

### addDocument(DocumentInfo document) {#addDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void addDocument(DocumentInfo document)
```


ドキュメントをドキュメントコレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) | DocumentInfo のインスタンスです。 |

### addPage(int documentIndex, int pageNumber) {#addPage-int-int-}
```
public final void addPage(int documentIndex, int pageNumber)
```


ページをページコレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| documentIndex | int | DocumentInfo のインデックスです。 |
| pageNumber | int | PageInfo の番号です。 |

### addPage(IPageInfo page) {#addPage-com.groupdocs.merger.domain.result.IPageInfo-}
```
public final void addPage(IPageInfo page)
```


ページをページコレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | [IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo) | PageInfo のインスタンスです。 |

### addPageRange(IPageInfo[] pages) {#addPageRange-com.groupdocs.merger.domain.result.IPageInfo---}
```
public final void addPageRange(IPageInfo[] pages)
```


ページをページコレクションに追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pages | [IPageInfo\[\]](../../com.groupdocs.merger.domain.result/ipageinfo) | Pages 配列です。 |

### clear() {#clear--}
```
public final void clear()
```


内部コレクションをクリアします。

