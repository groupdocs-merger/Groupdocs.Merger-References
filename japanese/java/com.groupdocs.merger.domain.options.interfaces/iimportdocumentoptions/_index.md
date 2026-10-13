---
title: "IImportDocumentOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "埋め込みドキュメントのインポート用インターフェイス。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
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
| [getObjectData()](#getObjectData--) | 埋め込みオブジェクトのデータです。 |
| [getExtension()](#getExtension--) | 埋め込みオブジェクトの拡張子です。 |
| [getPageNumber()](#getPageNumber--) | 埋め込みオブジェクトを挿入するページ番号です。 |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


埋め込みオブジェクトのデータです。

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


埋め込みオブジェクトの拡張子です。

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


埋め込みオブジェクトを挿入するページ番号です。

**Returns:**
int
