---
title: "IOleWordProcessingOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "OLE 経由で埋め込みドキュメントを Word 処理にインポートするオプション用インターフェイス。"
type: docs
weight: 20
url: /ja/java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

OLE 経由で埋め込みドキュメントを Word 処理にインポートするオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole オブジェクト画像の左座標。 |
| [setLeft(int value)](#setLeft-int-) | Ole オブジェクト画像の左座標。 |
| [getTop()](#getTop--) | Ole オブジェクト画像の上座標。 |
| [setTop(int value)](#setTop-int-) | Ole オブジェクト画像の上座標。 |
| [getImageData()](#getImageData--) | Ole オブジェクト画像のデータです。 |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Ole オブジェクト画像の左座標。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Ole オブジェクト画像の左座標。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole オブジェクト画像の上座標。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole オブジェクト画像の上座標。

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
