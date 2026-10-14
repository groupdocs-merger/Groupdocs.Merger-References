---
title: "OleDiagramOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供通过 OLE 将嵌入文档导入到 Diagram 的选项。"
type: docs
weight: 18
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

提供通过 OLE 将嵌入文档导入到 Diagram 的选项。

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | 初始化一个新的 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 类的实例。 |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | 初始化一个新的 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 类的实例。 |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | 初始化一个新的 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。 |
| [setX(int value)](#setX-int-) | 相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。 |
| [getY()](#getY--) | 相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。 |
| [setY(int value)](#setY-int-) | 相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。 |
| [getWidth()](#getWidth--) | 嵌入对象形状的宽度（英寸）。 |
| [setWidth(int value)](#setWidth-int-) | 嵌入对象形状的宽度（英寸）。 |
| [getHeight()](#getHeight--) | 嵌入对象形状的高度（英寸）。 |
| [setHeight(int value)](#setHeight-int-) | 嵌入对象形状的高度（英寸）。 |
| [getImageData()](#getImageData--) | 嵌入对象的图像数据。 |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


初始化一个新的 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectData | byte[] | 嵌入对象的数据。 |
| imageData | byte[] | 嵌入对象的图像数据。 |
| 扩展名 | java.lang.String | 嵌入对象的扩展名。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


初始化一个新的 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| imageData | byte[] | 嵌入对象的图像数据。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


初始化一个新的 [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### getX() {#getX--}
```
public final int getX()
```


相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


嵌入对象形状的宽度（英寸）。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


嵌入对象形状的宽度（英寸）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


嵌入对象形状的高度（英寸）。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


嵌入对象形状的高度（英寸）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


嵌入对象的图像数据。

**Returns:**
byte[]
