---
title: "IOleSpreadsheetOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于通过 OLE 将嵌入式文档导入到 Spreadsheet 的选项接口。"
type: docs
weight: 19
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleSpreadsheetOptions extends IImportDocumentOptions, ISizeOptions
```

用于通过 OLE 将嵌入式文档导入到 Spreadsheet 的选项接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 左上行索引。 |
| [setRowIndex(int value)](#setRowIndex-int-) | 左上行索引。 |
| [getColumnIndex()](#getColumnIndex--) | 左上列索引。 |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 左上列索引。 |
| [getImageData()](#getImageData--) | Ole 对象图像的数据。 |
### getRowIndex() {#getRowIndex--}
```
public abstract int getRowIndex()
```


左上行索引。

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public abstract void setRowIndex(int value)
```


左上行索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public abstract int getColumnIndex()
```


左上列索引。

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public abstract void setColumnIndex(int value)
```


左上列索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Ole 对象图像的数据。

**Returns:**
byte[]
