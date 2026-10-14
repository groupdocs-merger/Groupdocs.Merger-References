---
title: "OrientationOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供页面方向的选项。"
type: docs
weight: 23
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

提供页面方向的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | 初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。 |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | 初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。 |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | 初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。 |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | 初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMode()](#getMode--) | 获取页面方向的模式。 |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 的方向模式。 |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 的方向模式。 |
| pageNumbers | int[] | 页码。 |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 的方向模式。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


初始化一个新的 [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) 的方向模式。 |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### getMode() {#getMode--}
```
public final int getMode()
```


获取页面方向的模式。

**Returns:**
int
