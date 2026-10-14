---
title: "OleDiagramOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介して埋め込みドキュメントを Diagram にインポートするオプションを提供します。"
type: docs
weight: 18
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

OLE を介して埋め込みドキュメントを Diagram にインポートするオプションを提供します。

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | 新しいインスタンスの [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスを初期化します。 |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | 新しいインスタンスの [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスを初期化します。 |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | 新しいインスタンスの [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。 |
| [setX(int value)](#setX-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。 |
| [getY()](#getY--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。 |
| [setY(int value)](#setY-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。 |
| [getWidth()](#getWidth--) | 埋め込みオブジェクト形状の幅（インチ）。 |
| [setWidth(int value)](#setWidth-int-) | 埋め込みオブジェクト形状の幅（インチ）。 |
| [getHeight()](#getHeight--) | 埋め込みオブジェクト形状の高さ（インチ）。 |
| [setHeight(int value)](#setHeight-int-) | 埋め込みオブジェクト形状の高さ（インチ）。 |
| [getImageData()](#getImageData--) | 埋め込みオブジェクトの画像データ。 |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


新しいインスタンスの [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータ。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データ。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


新しいインスタンスの [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データ。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


新しいインスタンスの [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getX() {#getX--}
```
public final int getX()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


埋め込みオブジェクト形状の幅（インチ）。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


埋め込みオブジェクト形状の幅（インチ）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


埋め込みオブジェクト形状の高さ（インチ）。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


埋め込みオブジェクト形状の高さ（インチ）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


埋め込みオブジェクトの画像データ。

**Returns:**
byte[]
