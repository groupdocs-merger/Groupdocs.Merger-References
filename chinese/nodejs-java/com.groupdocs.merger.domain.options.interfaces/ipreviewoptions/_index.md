---
title: "IPreviewOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于预览选项的接口。"
type: docs
weight: 28
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

用于预览选项的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 预览宽度。 |
| [setWidth(int value)](#setWidth-int-) | 预览宽度。 |
| [getHeight()](#getHeight--) | 预览高度。 |
| [setHeight(int value)](#setHeight-int-) | 预览高度。 |
| [getResolution()](#getResolution--) | 图像分辨率。 |
| [setResolution(int value)](#setResolution-int-) | 图像分辨率。 |
| [getMode()](#getMode--) | 获取预览模式。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 验证拆分选项。 |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | 获取带有指定扩展名的按页号预览文档的完整文件路径。 |
| [getPageStreamFactory()](#getPageStreamFactory--) | 定义创建输出页面预览流方法的委托。 |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


预览宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


预览宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


预览高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


预览高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


图像分辨率。

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


图像分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


获取预览模式。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


验证拆分选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 文件类型为 [FileType](../../com.groupdocs.merger.domain/filetype) 类。 |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


获取带有指定扩展名的按页号预览文档的完整文件路径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | int | 预览的页码。 |
| 扩展名 | java.lang.String | 文件的扩展名。 |

**Returns:**
java.lang.String - 完整文件路径。
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


定义创建输出页面预览流方法的委托。

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
