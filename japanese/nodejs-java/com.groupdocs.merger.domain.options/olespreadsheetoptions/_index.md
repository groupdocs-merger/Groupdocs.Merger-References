---
title: "OleSpreadsheetOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介して埋め込みドキュメントを Spreadsheet にインポートするオプションを提供します。"
type: docs
weight: 20
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

OLE を介して埋め込みドキュメントを Spreadsheet にインポートするオプションを提供します。

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | 新しい[OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions)クラスのインスタンスを初期化します。 |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | 新しい[OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions)クラスのインスタンスを初期化します。 |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | 新しい[OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions)クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 左上の行インデックスです。 |
| [setRowIndex(int value)](#setRowIndex-int-) | 左上の行インデックスです。 |
| [getColumnIndex()](#getColumnIndex--) | 左上の列インデックスです。 |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 左上の列インデックスです。 |
| [getWidth()](#getWidth--) | Oleオブジェクト画像の幅です。 |
| [setWidth(int value)](#setWidth-int-) | Oleオブジェクト画像の幅です。 |
| [getHeight()](#getHeight--) | Oleオブジェクト画像の高さです。 |
| [setHeight(int value)](#setHeight-int-) | Oleオブジェクト画像の高さです。 |
| [getImageData()](#getImageData--) | Ole オブジェクト画像のデータです。 |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


新しい[OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータ。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データ。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


新しい[OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データ。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


新しい[OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


左上の行インデックスです。

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


左上の行インデックスです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


左上の列インデックスです。

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


左上の列インデックスです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Oleオブジェクト画像の幅です。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Oleオブジェクト画像の幅です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Oleオブジェクト画像の高さです。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Oleオブジェクト画像の高さです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole オブジェクト画像のデータです。

**Returns:**
byte[]
