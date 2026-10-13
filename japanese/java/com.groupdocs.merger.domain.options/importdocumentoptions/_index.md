---
title: "ImportDocumentOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "埋め込みドキュメントのインポート用オプションを提供します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.merger.domain.options/importdocumentoptions/
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
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | 新しいインスタンスを初期化します [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラス。 |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | 新しいインスタンスを初期化します [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getObjectData()](#getObjectData--) | 埋め込みオブジェクトのデータです。 |
| [getExtension()](#getExtension--) | 埋め込みオブジェクトの拡張子です。 |
| [getPageNumber()](#getPageNumber--) | 埋め込みオブジェクトを挿入するページ番号です。 |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | 埋め込みオブジェクトの画像データを取得します。 |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


新しいインスタンスを初期化します [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータです。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子です。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


新しいインスタンスを初期化します [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions) クラス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


埋め込みオブジェクトのデータです。

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


埋め込みオブジェクトの拡張子です。

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


埋め込みオブジェクトを挿入するページ番号です。

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
