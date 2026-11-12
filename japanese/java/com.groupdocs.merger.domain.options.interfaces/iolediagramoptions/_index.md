---
title: "IOleDiagramOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "OLE 経由で埋め込みドキュメントを Diagram にインポートするオプション用インターフェイス。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

OLE 経由で埋め込みドキュメントを Diagram にインポートするオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getX()](#getX--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。 |
| [setX(int value)](#setX-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。 |
| [getY()](#getY--) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。 |
| [setY(int value)](#setY-int-) | ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。 |
| [getImageData()](#getImageData--) | 埋め込みオブジェクトの画像データです。 |
### getX() {#getX--}
```
public abstract int getX()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の X 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


ページに対する埋め込みオブジェクト形状のピン（回転中心）の Y 座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


埋め込みオブジェクトの画像データです。

**Returns:**
byte[]
