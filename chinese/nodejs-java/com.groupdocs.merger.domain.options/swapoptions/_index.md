---
title: "SwapOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供交换文档页面的选项。"
type: docs
weight: 37
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/swapoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions)
```
public class SwapOptions implements ISwapOptions
```

提供交换文档页面的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SwapOptions(int firstPageNumber, int secondPageNumber)](#SwapOptions-int-int-) | 初始化一个新的 [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFirstPageNumber()](#getFirstPageNumber--) | 要交换的第一页码。 |
| [getSecondPageNumber()](#getSecondPageNumber--) | 要交换的第二页码。 |
### SwapOptions(int firstPageNumber, int secondPageNumber) {#SwapOptions-int-int-}
```
public SwapOptions(int firstPageNumber, int secondPageNumber)
```


初始化一个新的 [SwapOptions](../../com.groupdocs.merger.domain.options/swapoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstPageNumber | int | 第一页的页码。 |
| secondPageNumber | int | 第二页的页码。 |

### getFirstPageNumber() {#getFirstPageNumber--}
```
public final int getFirstPageNumber()
```


要交换的第一页码。

**Returns:**
int
### getSecondPageNumber() {#getSecondPageNumber--}
```
public final int getSecondPageNumber()
```


要交换的第二页码。

**Returns:**
int
