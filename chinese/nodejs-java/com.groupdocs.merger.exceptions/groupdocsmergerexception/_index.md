---
title: "GroupDocsMergerException"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "表示在文档处理期间发生的错误。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.merger.exceptions/groupdocsmergerexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception
```
public class GroupDocsMergerException extends Exception
```

表示在文档处理期间发生的错误。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GroupDocsMergerException(String message)](#GroupDocsMergerException-java.lang.String-) | 初始化一个新的 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 类的实例。 |
| [GroupDocsMergerException(String message, Exception innerException)](#GroupDocsMergerException-java.lang.String-java.lang.Exception-) | 初始化一个新的 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 类的实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getException(Exception exception)](#getException-java.lang.Exception-) | 从输入异常获取 GroupDocs Merger 异常。 |
### GroupDocsMergerException(String message) {#GroupDocsMergerException-java.lang.String-}
```
public GroupDocsMergerException(String message)
```


初始化一个新的 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 描述错误的消息。 |

### GroupDocsMergerException(String message, Exception innerException) {#GroupDocsMergerException-java.lang.String-java.lang.Exception-}
```
public GroupDocsMergerException(String message, Exception innerException)
```


初始化一个新的 [GroupDocsMergerException](../../com.groupdocs.merger.exceptions/groupdocsmergerexception) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 描述错误的消息。 |
| innerException | java.lang.Exception | 错误的内部异常。 |

### getException(Exception exception) {#getException-java.lang.Exception-}
```
public static Exception getException(Exception exception)
```


从输入异常获取 GroupDocs Merger 异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 异常 | java.lang.Exception | 输入异常。 |

**Returns:**
java.lang.Exception -
