---
title: "IOleSpreadsheetOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "OLE を介した埋め込みドキュメントの Spreadsheet へのインポートオプション用インターフェイス。"
type: docs
weight: 19
url: /ja/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

OLE を介した埋め込みドキュメントの Spreadsheet へのインポートオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 左上の行インデックスです。 |
| [setRowIndex(int value)](#setRowIndex-int-) | 左上の行インデックスです。 |
| [getColumnIndex()](#getColumnIndex--) | 左上の列インデックスです。 |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 左上の列インデックスです。 |
| [getImageData()](#getImageData--) | Ole オブジェクト画像のデータです。 |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


左上の行インデックスです。

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


左上の行インデックスです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


左上の列インデックスです。

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


左上の列インデックスです。

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
