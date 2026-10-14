---
title: "PreviewOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "表示文档预览选项。"
type: docs
weight: 29
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

表示文档预览选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | 初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。 |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | 初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。 |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | 初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。 |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | 初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 预览宽度。 |
| [setWidth(int value)](#setWidth-int-) | 预览宽度。 |
| [getHeight()](#getHeight--) | 预览高度。 |
| [setHeight(int value)](#setHeight-int-) | 预览高度。 |
| [getResolution()](#getResolution--) | 图像分辨率。 |
| [setResolution(int value)](#setResolution-int-) | 图像分辨率。 |
| [getMode()](#getMode--) | 预览模式。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 验证预览选项。 |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | 获取带有指定扩展名的按页号预览文档的完整文件路径。 |
| [getPageStreamFactory()](#getPageStreamFactory--) | 用于创建或释放输出页预览流的 PageStreamFactory。 |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 实例化用于写入输出页数据的流的方法。 |
| previewMode | int | 预览模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 实例化用于写入输出页数据的流的方法。 |
| previewMode | int | 预览模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | 页码。 |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 实例化用于写入输出页数据的流的方法。 |
| previewMode | int | 预览模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


初始化一个新的 [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | 实例化用于写入输出页数据的流的方法。 |
| previewMode | int | 预览模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


预览宽度。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


预览宽度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


预览高度。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


预览高度。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


图像分辨率。

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


图像分辨率。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


预览模式。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


验证预览选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 文件类型。 |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
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
public PageStreamFactory getPageStreamFactory()
```


用于创建或释放输出页预览流的 PageStreamFactory。

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
