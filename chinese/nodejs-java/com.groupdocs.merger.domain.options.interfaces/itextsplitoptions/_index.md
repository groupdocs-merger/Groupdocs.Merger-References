---
title: "ITextSplitOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "用于文本拆分选项的接口。"
type: docs
weight: 35
url: /zh/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

用于文本拆分选项的接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | 文本拆分的行号。 |
| [getMode()](#getMode--) | 文本拆分的模式。 |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | 验证拆分选项。 |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | 获取按索引并使用指定扩展名的已拆分文档的完整文件路径。 |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | 定义创建输出拆分流方法的委托。 |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


文本拆分的行号。

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


文本拆分的模式。

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

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


定义创建输出拆分流方法的委托。

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
