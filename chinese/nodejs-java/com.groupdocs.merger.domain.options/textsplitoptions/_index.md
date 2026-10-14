---
title: "TextSplitOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供文档文本拆分的选项。"
type: docs
weight: 39
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

提供文档文本拆分的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | 初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。 |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | 初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。 |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | 初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。 |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | 初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。 |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | 初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。 |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | 初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMode()](#getMode--) | 文本拆分的模式。 |
| [getLineNumbers()](#getLineNumbers--) | 文本拆分的行号。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 验证拆分选项。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 获取按索引并使用指定扩展名的已拆分文档的完整文件路径。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | SplitStreamFactory 用于创建或释放输出页面预览流。 |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lineNumbers | int[] | 文本拆分的行号。 |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | int | 文本拆分的模式。 |
| lineNumbers | int[] | 文本拆分的行号。 |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\\{0\\}.doc' 或 'c:/split\\{0\\}.\\{1\\}'，已包含定义的扩展名。 |
| lineNumbers | int[] | 文本拆分的行号。 |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'c:/split\\{0\\}.doc' 或 'c:/split\\{0\\}.\\{1\\}'，已包含定义的扩展名。 |
| mode | int | 文本拆分的模式。 |
| lineNumbers | int[] | 文本拆分的行号。 |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| lineNumbers | int[] | 文本拆分的行号。 |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


初始化一个新的 [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | 用于实例化写入输出拆分数据的流的方法。 |
| mode | int | 文本拆分的模式。 |
| lineNumbers | int[] | 文本拆分的行号。 |

### getMode() {#getMode--}
```
public final int getMode()
```


文本拆分的模式。

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


文本拆分的行号。

**Returns:**
int[]
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


获取按索引并使用指定扩展名的已拆分文档的完整文件路径。

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
