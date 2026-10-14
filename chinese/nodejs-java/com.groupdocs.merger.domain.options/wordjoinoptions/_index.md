---
title: "WordJoinOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "Word 合并选项。"
type: docs
weight: 43
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Word 合并选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | 初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMode()](#getMode--) | Word 连接模式。 |
| [setMode(int value)](#setMode-int-) | Word 连接模式。 |
| [getCompliance()](#getCompliance--) | Word Ooxml 格式的合规模式 |
| [setCompliance(int value)](#setCompliance-int-) | Word Ooxml 格式的合规模式 |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumbers | int[] | 页码。 |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |
| pageNumbers | int[] | 页码。 |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


初始化一个新的 [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### getMode() {#getMode--}
```
public final int getMode()
```


Word 连接模式。

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Word 连接模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Word Ooxml 格式的合规模式

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Word Ooxml 格式的合规模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

