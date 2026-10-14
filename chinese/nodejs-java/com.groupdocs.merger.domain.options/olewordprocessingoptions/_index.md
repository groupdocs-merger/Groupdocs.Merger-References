---
title: "OleWordProcessingOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供通过 OLE 将嵌入文档导入到 Word processing 的选项。"
type: docs
weight: 21
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

提供通过 OLE 将嵌入文档导入到 Word processing 的选项。

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | 初始化 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 类的新实例。 |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | 初始化 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 类的新实例。 |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | 初始化 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole 对象图像的左坐标。 |
| [setLeft(int value)](#setLeft-int-) | Ole 对象图像的左坐标。 |
| [getTop()](#getTop--) | Ole 对象图像的上坐标。 |
| [setTop(int value)](#setTop-int-) | Ole 对象图像的上坐标。 |
| [getWidth()](#getWidth--) | Ole 对象图像的宽度。 |
| [setWidth(int value)](#setWidth-int-) | Ole 对象图像的宽度。 |
| [getHeight()](#getHeight--) | Ole 对象图像的高度。 |
| [setHeight(int value)](#setHeight-int-) | Ole 对象图像的高度。 |
| [getImageData()](#getImageData--) | Ole 对象图像的数据。 |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


初始化 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectData | byte[] | 嵌入对象的数据。 |
| imageData | byte[] | 嵌入对象的图像数据。 |
| 扩展名 | java.lang.String | 嵌入对象的扩展名。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


初始化 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| imageData | byte[] | 嵌入对象的图像数据。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


初始化 [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Ole 对象图像的左坐标。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Ole 对象图像的左坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Ole 对象图像的上坐标。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Ole 对象图像的上坐标。

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
