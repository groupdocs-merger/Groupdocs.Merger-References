---
title: "MoveOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供移动文档页面的选项。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/moveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions)
```
public class MoveOptions implements IMoveOptions
```

提供移动文档页面的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MoveOptions(int pageNumberToMove, int newPageNumber)](#MoveOptions-int-int-) | 初始化一个新的 [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageNumberToMove()](#getPageNumberToMove--) | 获取或设置要移动的页码。 |
| [getNewPageNumber()](#getNewPageNumber--) | 获取或设置新的页码。 |
### MoveOptions(int pageNumberToMove, int newPageNumber) {#MoveOptions-int-int-}
```
public MoveOptions(int pageNumberToMove, int newPageNumber)
```


初始化一个新的 [MoveOptions](../../com.groupdocs.merger.domain.options/moveoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumberToMove | int | 要移动的页码。 |
| newPageNumber | int | 新的页码。 |

### getPageNumberToMove() {#getPageNumberToMove--}
```
public final int getPageNumberToMove()
```


获取或设置要移动的页码。

值：要移动的页码。

**Returns:**
int
### getNewPageNumber() {#getNewPageNumber--}
```
public final int getNewPageNumber()
```


获取或设置新的页码。

值：新的页码。

**Returns:**
int
