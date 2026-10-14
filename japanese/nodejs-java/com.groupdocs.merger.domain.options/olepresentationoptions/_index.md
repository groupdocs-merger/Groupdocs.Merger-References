---
title: "OlePresentationOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介して埋め込みドキュメントを Presentation にインポートするオプションを提供します。"
type: docs
weight: 19
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

OLE を介して埋め込みドキュメントを Presentation にインポートするオプションを提供します。

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | 新しいインスタンスの [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) クラスを初期化します。 |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | 新しいインスタンスの [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) クラスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | 埋め込みオブジェクトフレームの X 座標です。 |
| [setX(int value)](#setX-int-) | 埋め込みオブジェクトフレームの X 座標です。 |
| [getY()](#getY--) | 埋め込みオブジェクトフレームの Y 座標です。 |
| [setY(int value)](#setY-int-) | 埋め込みオブジェクトフレームの Y 座標です。 |
| [getWidth()](#getWidth--) | 埋め込みオブジェクトフレームの幅です。 |
| [setWidth(int value)](#setWidth-int-) | 埋め込みオブジェクトフレームの幅です。 |
| [getHeight()](#getHeight--) | 埋め込みオブジェクトフレームの高さです。 |
| [setHeight(int value)](#setHeight-int-) | 埋め込みオブジェクトフレームの高さです。 |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


新しいインスタンスの [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| objectData | byte[] | 埋め込みオブジェクトのデータ。 |
| 拡張子 | java.lang.String | 埋め込みオブジェクトの拡張子。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


新しいインスタンスの [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) クラスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | 埋め込みオブジェクトのファイルパスです。 |
| pageNumber | int | 埋め込みオブジェクトを追加するページ番号です。 |

### getX() {#getX--}
```
public final int getX()
```


埋め込みオブジェクトフレームの X 座標です。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


埋め込みオブジェクトフレームの X 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


埋め込みオブジェクトフレームの Y 座標です。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


埋め込みオブジェクトフレームの Y 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


埋め込みオブジェクトフレームの幅です。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


埋め込みオブジェクトフレームの幅です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


埋め込みオブジェクトフレームの高さです。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


埋め込みオブジェクトフレームの高さです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

