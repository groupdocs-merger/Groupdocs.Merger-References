---
title: "IPreviewOptions"
second_title: "Java 用 GroupDocs.Merger API リファレンス"
description: "プレビューオプション用インターフェイス。"
type: docs
weight: 28
url: /ja/java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

プレビューオプション用インターフェイス。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | プレビュー幅。 |
| [setWidth(int value)](#setWidth-int-) | プレビュー幅。 |
| [getHeight()](#getHeight--) | プレビュー高さ。 |
| [setHeight(int value)](#setHeight-int-) | プレビュー高さ。 |
| [getResolution()](#getResolution--) | 画像解像度。 |
| [setResolution(int value)](#setResolution-int-) | 画像解像度。 |
| [getMode()](#getMode--) | プレビューのモードを取得します。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 分割オプションを検証します。 |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | ページ番号と定義された拡張子でプレビューされたドキュメントの完全なファイルパスを取得します。 |
| [getPageStreamFactory()](#getPageStreamFactory--) | 出力ページプレビュー ストリームを作成するメソッドを定義するデリゲート。 |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


プレビュー幅。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


プレビュー幅。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


プレビュー高さ。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


プレビュー高さ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


画像解像度。

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


画像解像度。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


プレビューのモードを取得します。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


分割オプションを検証します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | クラス [FileType](../../com.groupdocs.merger.domain/filetype) のファイルタイプです。 |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


ページ番号と定義された拡張子でプレビューされたドキュメントの完全なファイルパスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | int | プレビューのページ番号。 |
| 拡張子 | java.lang.String | ファイルの拡張子。 |

**Returns:**
java.lang.String - 完全なファイルパスです。
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


出力ページプレビュー ストリームを作成するメソッドを定義するデリゲート。

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
