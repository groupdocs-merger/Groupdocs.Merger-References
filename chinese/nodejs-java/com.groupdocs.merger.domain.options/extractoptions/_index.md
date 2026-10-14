---
title: "ExtractOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供提取文档页面的选项。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/extractoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions)
```
public class ExtractOptions extends PageOptions implements IExtractOptions
```

提供提取文档页面的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExtractOptions()](#ExtractOptions--) | 初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。 |
| [ExtractOptions(int[] pageNumbers)](#ExtractOptions-int---) | 初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。 |
| [ExtractOptions(int startNumber, int endNumber)](#ExtractOptions-int-int-) | 初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。 |
| [ExtractOptions(int startNumber, int endNumber, int mode)](#ExtractOptions-int-int-int-) | 初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。 |
### ExtractOptions() {#ExtractOptions--}
```
public ExtractOptions()
```


初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。

### ExtractOptions(int[] pageNumbers) {#ExtractOptions-int---}
```
public ExtractOptions(int[] pageNumbers)
```


初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumbers | int[] | 页码。 |

### ExtractOptions(int startNumber, int endNumber) {#ExtractOptions-int-int-}
```
public ExtractOptions(int startNumber, int endNumber)
```


初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### ExtractOptions(int startNumber, int endNumber, int mode) {#ExtractOptions-int-int-int-}
```
public ExtractOptions(int startNumber, int endNumber, int mode)
```


初始化一个新的 [ExtractOptions](../../com.groupdocs.merger.domain.options/extractoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

