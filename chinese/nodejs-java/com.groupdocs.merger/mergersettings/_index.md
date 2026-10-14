---
title: "MergerSettings"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "定义用于自定义行为的设置。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.merger/mergersettings/
---
**Inheritance:**
java.lang.Object
```
public class MergerSettings
```

定义用于自定义 [Merger](../../com.groupdocs.merger/merger) 行为的设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MergerSettings()](#MergerSettings--) | 初始化 [MergerSettings](../../com.groupdocs.merger/mergersettings) 类的新实例。 |
| [MergerSettings(ILogger logger)](#MergerSettings-com.groupdocs.merger.logging.ILogger-) | 初始化 [MergerSettings](../../com.groupdocs.merger/mergersettings) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLogger()](#getLogger--) | 用于跟踪文档处理工作流的日志实现。 |
| [setLogger(ILogger value)](#setLogger-com.groupdocs.merger.logging.ILogger-) | 用于跟踪文档处理工作流的日志实现。 |
### MergerSettings() {#MergerSettings--}
```
public MergerSettings()
```


初始化 [MergerSettings](../../com.groupdocs.merger/mergersettings) 类的新实例。

### MergerSettings(ILogger logger) {#MergerSettings-com.groupdocs.merger.logging.ILogger-}
```
public MergerSettings(ILogger logger)
```


初始化 [MergerSettings](../../com.groupdocs.merger/mergersettings) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.merger.logging/ilogger) | 日志实现。 |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


用于跟踪文档处理工作流的日志实现。

**Returns:**
[ILogger](../../com.groupdocs.merger.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.merger.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


用于跟踪文档处理工作流的日志实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.merger.logging/ilogger) |  |

