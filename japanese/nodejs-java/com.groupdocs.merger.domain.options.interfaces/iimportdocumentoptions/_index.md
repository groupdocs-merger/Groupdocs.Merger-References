---
title: "IImportDocumentOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "埋め込みドキュメントのインポート用インターフェイス。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

埋め込みドキュメントのインポート用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 埋め込みオブジェクトのデータ。 |
| [getExtension()](#getExtension--) | 埋め込みオブジェクトの拡張子。 |
| [getPageNumber()](#getPageNumber--) | 埋め込みオブジェクトを挿入するページ番号。 |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


埋め込みオブジェクトのデータ。

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


埋め込みオブジェクトの拡張子。

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


埋め込みオブジェクトを挿入するページ番号。

**Returns:**
int
