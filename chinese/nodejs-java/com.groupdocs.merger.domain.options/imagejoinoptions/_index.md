---
title: "ImageJoinOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "图像合并选项。"
type: docs
weight: 13
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

图像合并选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | 初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。 |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | 初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。 |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | 初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。 |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | 初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 图像文件类型。 |
| [getMode()](#getMode--) | 图像合并模式。 |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 图像文件类型。 |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageJoinMode | int | 图像合并模式。 |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


初始化 [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 图像文件类型。 |
| imageJoinMode | int | 图像合并模式。 |

### getType() {#getType--}
```
public final FileType getType()
```


图像文件类型。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


图像合并模式。

**Returns:**
int
