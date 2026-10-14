---
title: "RemoveOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供页面删除的选项。"
type: docs
weight: 31
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/removeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions)
```
public class RemoveOptions extends PageOptions implements IRemoveOptions
```

提供页面删除的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RemoveOptions()](#RemoveOptions--) | 初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。 |
| [RemoveOptions(int[] pageNumbers)](#RemoveOptions-int---) | 初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。 |
| [RemoveOptions(int startNumber, int endNumber)](#RemoveOptions-int-int-) | 初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。 |
| [RemoveOptions(int startNumber, int endNumber, int mode)](#RemoveOptions-int-int-int-) | 初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。 |
### RemoveOptions() {#RemoveOptions--}
```
public RemoveOptions()
```


初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。

### RemoveOptions(int[] pageNumbers) {#RemoveOptions-int---}
```
public RemoveOptions(int[] pageNumbers)
```


初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumbers | int[] | 页码。 |

### RemoveOptions(int startNumber, int endNumber) {#RemoveOptions-int-int-}
```
public RemoveOptions(int startNumber, int endNumber)
```


初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### RemoveOptions(int startNumber, int endNumber, int mode) {#RemoveOptions-int-int-int-}
```
public RemoveOptions(int startNumber, int endNumber, int mode)
```


初始化 [RemoveOptions](../../com.groupdocs.merger.domain.options/removeoptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

