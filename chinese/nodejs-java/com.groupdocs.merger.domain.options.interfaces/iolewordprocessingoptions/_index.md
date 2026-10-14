---
title: "IOleWordProcessingOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于通过 OLE 将嵌入式文档导入到 Word processing 的选项接口。"
type: docs
weight: 20
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

用于通过 OLE 将嵌入式文档导入到 Word processing 的选项接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLeft()](#getLeft--) | Ole 对象图像的左坐标。 |
| [setLeft(int value)](#setLeft-int-) | Ole 对象图像的左坐标。 |
| [getTop()](#getTop--) | Ole 对象图像的上坐标。 |
| [setTop(int value)](#setTop-int-) | Ole 对象图像的上坐标。 |
| [getImageData()](#getImageData--) | Ole 对象图像的数据。 |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Ole 对象图像的左坐标。

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Ole 对象图像的左坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Ole 对象图像的上坐标。

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Ole 对象图像的上坐标。

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
