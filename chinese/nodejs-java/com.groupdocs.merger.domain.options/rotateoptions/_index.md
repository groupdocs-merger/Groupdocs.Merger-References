---
title: "RotateOptions"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "提供页面旋转的选项。"
type: docs
weight: 33
url: /zh/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

提供页面旋转的选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | 初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。 |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | 初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。 |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | 初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。 |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | 初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMode()](#getMode--) | 获取旋转模式（90、180 或 270 度）。 |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateMode | int | 旋转模式 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateMode | int | 旋转模式 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| pageNumbers | int[] | 页码。 |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateMode | int | 旋转模式 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


初始化一个新的 [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateMode | int | 旋转模式 (\\#getMode.getMode/\\#setMode(int).setMode(int)) |
| startNumber | int | 起始页码。 |
| endNumber | int | 结束页码。 |
| mode | int | 范围模式。 |

### getMode() {#getMode--}
```
public final int getMode()
```


获取旋转模式（90、180 或 270 度）。

**Returns:**
int
