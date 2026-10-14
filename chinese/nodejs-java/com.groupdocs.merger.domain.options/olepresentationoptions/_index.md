---
title: "OlePresentationOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供通过 OLE 将嵌入文档导入到 Presentation 的选项。"
type: docs
weight: 19
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

提供通过 OLE 将嵌入文档导入到 Presentation 的选项。

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | 初始化一个新的 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 类的实例。 |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | 初始化一个新的 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 嵌入对象框架的 X 坐标。 |
| [setX(int value)](#setX-int-) | 嵌入对象框架的 X 坐标。 |
| [getY()](#getY--) | 嵌入对象框架的 Y 坐标。 |
| [setY(int value)](#setY-int-) | 嵌入对象框架的 Y 坐标。 |
| [getWidth()](#getWidth--) | 嵌入对象框架的宽度。 |
| [setWidth(int value)](#setWidth-int-) | 嵌入对象框架的宽度。 |
| [getHeight()](#getHeight--) | 嵌入对象框架的高度。 |
| [setHeight(int value)](#setHeight-int-) | 嵌入对象框架的高度。 |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


初始化一个新的 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| objectData | byte[] | 嵌入对象的数据。 |
| 扩展名 | java.lang.String | 嵌入对象的扩展名。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


初始化一个新的 [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 嵌入对象的文件路径。 |
| pageNumber | int | 用于添加嵌入对象的页码。 |

### getX() {#getX--}
```
public final int getX()
```


嵌入对象框架的 X 坐标。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


嵌入对象框架的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


嵌入对象框架的 Y 坐标。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


嵌入对象框架的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


嵌入对象框架的宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


嵌入对象框架的宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


嵌入对象框架的高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


嵌入对象框架的高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

