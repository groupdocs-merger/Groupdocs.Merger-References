---
title: "IOleWordProcessingOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介した埋め込みドキュメントの Word 処理へのインポートオプション用インターフェイス。"
type: docs
weight: 20
url: /ja/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

OLE を介した埋め込みドキュメントの Word 処理へのインポートオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole オブジェクト画像の左座標です。 |
| [setLeft(int value)](#setLeft-int-) | Ole オブジェクト画像の左座標です。 |
| [getTop()](#getTop--) | Ole オブジェクト画像の上座標です。 |
| [setTop(int value)](#setTop-int-) | Ole オブジェクト画像の上座標です。 |
| [getImageData()](#getImageData--) | Ole オブジェクト画像のデータです。 |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Ole オブジェクト画像の左座標です。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Ole オブジェクト画像の左座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole オブジェクト画像の上座標です。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole オブジェクト画像の上座標です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole オブジェクト画像のデータです。

**Returns:**
byte[]
