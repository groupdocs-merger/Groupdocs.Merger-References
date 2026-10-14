---
title: "PreviewOptions"
second_title: "Node.js 用 GroupDocs.Merger (Java 経由) API リファレンス"
description: "ドキュメントプレビューオプションを表します。"
type: docs
weight: 29
url: /ja/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

ドキュメントプレビューオプションを表します。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | 新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。 |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | 新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。 |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | 新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。 |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | 新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWidth()](#getWidth--) | プレビュー幅です。 |
| [setWidth(int value)](#setWidth-int-) | プレビュー幅です。 |
| [getHeight()](#getHeight--) | プレビュー高さです。 |
| [setHeight(int value)](#setHeight-int-) | プレビュー高さです。 |
| [getResolution()](#getResolution--) | 画像解像度です。 |
| [setResolution(int value)](#setResolution-int-) | 画像解像度です。 |
| [getMode()](#getMode--) | プレビューのモードです。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | プレビューオプションを検証します。 |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | ページ番号と指定された拡張子に基づいて、プレビューされたドキュメントの完全なファイルパスを取得します。 |
| [getPageStreamFactory()](#getPageStreamFactory--) | 出力ページプレビュー ストリームを作成または解放するための PageStreamFactory。 |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| previewMode | int | Mode のプレビュー モード (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| previewMode | int | Mode のプレビュー モード (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | ページ番号です。 |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| previewMode | int | Mode のプレビュー モード (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


新しい [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 出力ページデータを書き込むために使用されるストリームをインスタンス化するメソッドです。 |
| previewMode | int | Mode のプレビュー モード (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 開始ページ番号です。 |
| endNumber | int | 終了ページ番号です。 |
| mode | int | 範囲モードです。 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


プレビュー幅です。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


プレビュー幅です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


プレビュー高さです。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


プレビュー高さです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


画像解像度です。

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


画像解像度です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


プレビューのモードです。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


プレビューオプションを検証します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | ファイルタイプです。 |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


ページ番号と指定された拡張子に基づいて、プレビューされたドキュメントの完全なファイルパスを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber | int | プレビューのページ番号です。 |
| 拡張子 | java.lang.String | ファイルの拡張子。 |

**Returns:**
java.lang.String - 完全なファイルパス。
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


出力ページプレビュー ストリームを作成または解放するための PageStreamFactory。

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
