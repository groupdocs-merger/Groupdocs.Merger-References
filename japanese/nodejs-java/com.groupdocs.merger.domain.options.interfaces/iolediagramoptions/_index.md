---
title: "IOleDiagramOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介した埋め込みドキュメントの Diagram へのインポートオプション用インターフェイス。"
type: docs
weight: 17
url: /ja/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

OLE を介した埋め込みドキュメントの Diagram へのインポートオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。 |
| [setX(int value)](#setX-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。 |
| [getY()](#getY--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。 |
| [setY(int value)](#setY-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。 |
| [getImageData()](#getImageData--) | 埋め込みオブジェクトの画像データ。 |
### getX() {#getX--}
```
public abstract int getX()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


埋め込みオブジェクトの画像データ。

**Returns:**
byte[]
