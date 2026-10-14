---
title: "OleWordProcessingOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介して埋め込みドキュメントを Word 処理にインポートするオプションを提供します。"
type: docs
weight: 21
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

OLE を介して埋め込みドキュメントを Word 処理にインポートするオプションを提供します。

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | 新しい[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions)クラスのインスタンスを初期化します。 |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | 新しい[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions)クラスのインスタンスを初期化します。 |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | 新しい[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions)クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole オブジェクト画像の左座標です。 |
| [setLeft(int value)](#setLeft-int-) | Ole オブジェクト画像の左座標です。 |
| [getTop()](#getTop--) | Ole オブジェクト画像の上座標です。 |
| [setTop(int value)](#setTop-int-) | Ole オブジェクト画像の上座標です。 |
| [getWidth()](#getWidth--) | Oleオブジェクト画像の幅です。 |
| [setWidth(int value)](#setWidth-int-) | Oleオブジェクト画像の幅です。 |
| [getHeight()](#getHeight--) | Oleオブジェクト画像の高さです。 |
| [setHeight(int value)](#setHeight-int-) | Oleオブジェクト画像の高さです。 |
| [getImageData()](#getImageData--) | Ole オブジェクト画像のデータです。 |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


新しい[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータ。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データ。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


新しい[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データ。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


新しい[OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions)クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ole オブジェクト画像の左座標です。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ole オブジェクト画像の左座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ole オブジェクト画像の上座標です。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ole オブジェクト画像の上座標です。

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
