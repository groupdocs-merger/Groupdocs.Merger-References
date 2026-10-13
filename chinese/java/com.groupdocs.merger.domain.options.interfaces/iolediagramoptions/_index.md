---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger 适用于 Java 的 API 参考"
description: "用于将嵌入式文档通过 OLE 导入到 Diagram 的选项接口。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

用于将嵌入式文档通过 OLE 导入到 Diagram 的选项接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 嵌入对象形状的针（旋转中心）相对于页面的 X 坐标。 |
| [setX(int value)](#setX-int-) | 嵌入对象形状的针（旋转中心）相对于页面的 X 坐标。 |
| [getY()](#getY--) | 嵌入对象形状的针（旋转中心）相对于页面的 Y 坐标。 |
| [setY(int value)](#setY-int-) | 嵌入对象形状的针（旋转中心）相对于页面的 Y 坐标。 |
| [getImageData()](#getImageData--) | 嵌入对象的图像数据。 |
### getX() {#getX--}
```
public abstract int getX()
```


嵌入对象形状的针（旋转中心）相对于页面的 X 坐标。

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


嵌入对象形状的针（旋转中心）相对于页面的 X 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


嵌入对象形状的针（旋转中心）相对于页面的 Y 坐标。

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


嵌入对象形状的针（旋转中心）相对于页面的 Y 坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


嵌入对象的图像数据。

**Returns:**
byte[]
