---
title: "OleSpreadsheetOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供通过 OLE 将嵌入文档导入到 Spreadsheet 的选项。"
type: docs
weight: 20
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/olespreadsheetoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleSpreadsheetOptions](../../com.groupdocs.merger.domain.options.interfaces/iolespreadsheetoptions)
```
public class OleSpreadsheetOptions extends ImportDocumentOptions implements IOleSpreadsheetOptions
```

提供通过 OLE 将嵌入文档导入到 Spreadsheet 的选项。

--------------------

**Learn more**

 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]


[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleSpreadsheetOptions-byte---byte---java.lang.String-int-) | 初始化 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 类的新实例。 |
| [OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-byte---int-) | 初始化 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 类的新实例。 |
| [OleSpreadsheetOptions(String filePath, int pageNumber)](#OleSpreadsheetOptions-java.lang.String-int-) | 初始化 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRowIndex()](#getRowIndex--) | 左上行索引。 |
| [setRowIndex(int value)](#setRowIndex-int-) | 左上行索引。 |
| [getColumnIndex()](#getColumnIndex--) | 左上列索引。 |
| [setColumnIndex(int value)](#setColumnIndex-int-) | 左上列索引。 |
| [getWidth()](#getWidth--) | Ole 对象图像的宽度。 |
| [setWidth(int value)](#setWidth-int-) | Ole 对象图像的宽度。 |
| [getHeight()](#getHeight--) | Ole 对象图像的高度。 |
| [setHeight(int value)](#setHeight-int-) | Ole 对象图像的高度。 |
| [getImageData()](#getImageData--) | Ole 对象图像的数据。 |
### OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleSpreadsheetOptions-byte---byte---java.lang.String-int-}
```
public OleSpreadsheetOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


初始化 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectData | byte[] | 嵌入对象的数据。 |
| imageData | byte[] | 嵌入对象的图像数据。 |
| 扩展名 | java.lang.String | 嵌入对象的扩展名。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-byte---int-}
```
public OleSpreadsheetOptions(String filePath, byte[] imageData, int pageNumber)
```


初始化 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| imageData | byte[] | 嵌入对象的图像数据。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OleSpreadsheetOptions(String filePath, int pageNumber) {#OleSpreadsheetOptions-java.lang.String-int-}
```
public OleSpreadsheetOptions(String filePath, int pageNumber)
```


初始化 [OleSpreadsheetOptions](../../com.groupdocs.merger.domain.options/olespreadsheetoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### getRowIndex() {#getRowIndex--}
```
public final int getRowIndex()
```


左上行索引。

**Returns:**
int
### setRowIndex(int value) {#setRowIndex-int-}
```
public final void setRowIndex(int value)
```


左上行索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColumnIndex() {#getColumnIndex--}
```
public final int getColumnIndex()
```


左上列索引。

**Returns:**
int
### setColumnIndex(int value) {#setColumnIndex-int-}
```
public final void setColumnIndex(int value)
```


左上列索引。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ole 对象图像的宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ole 对象图像的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ole 对象图像的高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ole 对象图像的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Ole 对象图像的数据。

**Returns:**
byte[]
