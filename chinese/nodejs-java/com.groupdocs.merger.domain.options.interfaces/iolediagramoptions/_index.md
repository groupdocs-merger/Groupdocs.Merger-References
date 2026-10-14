---
title: "IOleDiagramOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于通过 OLE 将嵌入式文档导入到 Diagram 的选项接口。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

用于通过 OLE 将嵌入式文档导入到 Diagram 的选项接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。 |
| [setX(int value)](#setX-int-) | 相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。 |
| [getY()](#getY--) | 相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。 |
| [setY(int value)](#setY-int-) | 相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。 |
| [getImageData()](#getImageData--) | 嵌入对象的图像数据。 |
### getX() {#getX--}
```
public abstract int getX()
```


相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


相对于页面，嵌入对象形状针（旋转中心）的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


相对于页面，嵌入对象形状针（旋转中心）的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


嵌入对象的图像数据。

**Returns:**
byte[]
