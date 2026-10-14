---
title: "PageJoinOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供文档合并的选项。"
type: docs
weight: 25
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

提供文档合并的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 要合并的文件类型。 |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumbers | int[] | 页码。 |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |
| pageNumbers | int[] | 页码。 |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


初始化 [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### getType() {#getType--}
```
public final FileType getType()
```


要合并的文件类型。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
