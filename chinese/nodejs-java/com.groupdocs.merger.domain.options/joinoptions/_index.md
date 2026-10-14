---
title: "JoinOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供文档合并的选项。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/joinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions)
```
public class JoinOptions implements IJoinOptions
```

提供文档合并的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JoinOptions()](#JoinOptions--) | 初始化一个新的 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 类的实例。 |
| [JoinOptions(FileType fileType)](#JoinOptions-com.groupdocs.merger.domain.FileType-) | 初始化一个新的 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 要合并的文件类型。 |
### JoinOptions() {#JoinOptions--}
```
public JoinOptions()
```


初始化一个新的 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 类的实例。

### JoinOptions(FileType fileType) {#JoinOptions-com.groupdocs.merger.domain.FileType-}
```
public JoinOptions(FileType fileType)
```


初始化一个新的 [JoinOptions](../../com.groupdocs.merger.domain.options/joinoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | 要合并的文件类型。 |

### getType() {#getType--}
```
public final FileType getType()
```


要合并的文件类型。

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
