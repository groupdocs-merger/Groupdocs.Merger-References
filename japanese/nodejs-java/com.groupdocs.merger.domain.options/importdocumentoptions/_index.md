---
title: "ImportDocumentOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "埋め込みドキュメントのインポート用オプションを提供します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

埋め込みドキュメントのインポート用オプションを提供します。

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]
 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]
 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]
 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]
 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | 新しいインスタンスの [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラスを初期化します。 |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | 新しいインスタンスの [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 埋め込みオブジェクトのデータ。 |
| [getExtension()](#getExtension--) | 埋め込みオブジェクトの拡張子。 |
| [getPageNumber()](#getPageNumber--) | 埋め込みオブジェクトを挿入するページ番号。 |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | 埋め込みオブジェクトの画像データを取得します。 |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


新しいインスタンスの [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータ。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


新しいインスタンスの [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


埋め込みオブジェクトのデータ。

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


埋め込みオブジェクトの拡張子。

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


埋め込みオブジェクトを挿入するページ番号。

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


埋め込みオブジェクトの画像データを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |

**Returns:**
byte[]
