---
title: "SplitOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供文档页面拆分的选项。"
type: docs
weight: 36
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

提供文档页面拆分的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | 初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMode()](#getMode--) | 获取页面拆分的模式。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 验证拆分选项。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 获取按索引分割的文档的完整文件路径，使用预定义的扩展名。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory 用于创建或释放输出页面预览流。 |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumbers | int[] | 页码。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\{0\}.doc' 或 'c:/split\{0\}.\{1\}'，已使用预定义的扩展名。 |
| pageNumbers | int[] | 页码。 |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\{0\}.doc' 或 'c:/split\{0\}.\{1\}'，已使用预定义的扩展名。 |
| pageNumbers | int[] | 页码。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\{0\}.doc' 或 'c:/split\{0\}.\{1\}'，已使用预定义的扩展名。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\{0\}.doc' 或 'c:/split\{0\}.\{1\}'，已使用预定义的扩展名。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\{0\}.doc' 或 'c:/split\{0\}.\{1\}'，已使用预定义的扩展名。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | java.lang.Integer | 范围模式。 |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\{0\}.doc' 或 'c:/split\{0\}.\{1\}'，已使用预定义的扩展名。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| pageNumbers | int[] | 页码。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| pageNumbers | int[] | 页码。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | java.lang.Integer | 范围模式。 |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


初始化 [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| splitMode | int | 分割模式的 Mode (\#getMode.getMode/\#setMode(int).setMode(int))。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### getMode() {#getMode--}
```
public final int getMode()
```


获取页面拆分的模式。

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


验证拆分选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 文件类型为 [FileType](../../com.groupdocs.merger.domain/filetype) 类。 |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


获取按索引分割的文档的完整文件路径，使用预定义的扩展名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | int | 拆分文档的索引。 |
| 扩展名 | java.lang.String | 文件的扩展名。 |

**Returns:**
java.lang.String - 完整文件路径。
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


SplitStreamFactory 用于创建或释放输出页面预览流。

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
