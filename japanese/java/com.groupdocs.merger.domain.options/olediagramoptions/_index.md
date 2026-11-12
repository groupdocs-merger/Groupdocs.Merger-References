---
title: "OleDiagramOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "OLE を介して埋め込みドキュメントを Diagram にインポートするためのオプションを提供します。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

OLE を介して埋め込みドキュメントを Diagram にインポートするためのオプションを提供します。

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | 新しい [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスのインスタンスを初期化します。 |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | 新しい [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスのインスタンスを初期化します。 |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | 新しい [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。 |
| [setX(int value)](#setX-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。 |
| [getY()](#getY--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。 |
| [setY(int value)](#setY-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。 |
| [getWidth()](#getWidth--) | 埋め込みオブジェクトの形状の幅（インチ）です。 |
| [setWidth(int value)](#setWidth-int-) | 埋め込みオブジェクトの形状の幅（インチ）です。 |
| [getHeight()](#getHeight--) | 埋め込みオブジェクトの形状の高さ（インチ）です。 |
| [setHeight(int value)](#setHeight-int-) | 埋め込みオブジェクトの形状の高さ（インチ）です。 |
| [getImageData()](#getImageData--) | 埋め込みオブジェクトの画像データです。 |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


新しい [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータです。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データです。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子です。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


新しい [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| imageData | byte[] | 埋め込みオブジェクトの画像データです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


新しい [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getX() {#getX--}
```
public final int getX()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


埋め込みオブジェクトの形状の幅（インチ）です。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


埋め込みオブジェクトの形状の幅（インチ）です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


埋め込みオブジェクトの形状の高さ（インチ）です。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


埋め込みオブジェクトの形状の高さ（インチ）です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


埋め込みオブジェクトの画像データです。

**Returns:**
byte[]
