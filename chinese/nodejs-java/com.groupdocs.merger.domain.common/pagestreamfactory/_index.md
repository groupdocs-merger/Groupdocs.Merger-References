---
title: "PageStreamFactory"
second_title: "适用于 Node.js via Java 的 GroupDocs.Merger API 参考"
description: "定义创建输出页面预览流方法的接口。"
type: docs
weight: 10
url: /zh/nodejs-java/com.groupdocs.merger.domain.common/pagestreamfactory/
---```
public interface PageStreamFactory
```

Interface that defines method to create output page preview stream.
## Methods

| Method | Description |
| --- | --- |
| [createPageStream(int pageNumber)](#createPageStream-int-) | Method to create output page preview stream. |
| [closePageStream(int pageNumber, OutputStream pageStream)](#closePageStream-int-java.io.OutputStream-) | Method to release output page preview stream |
### createPageStream(int pageNumber) {#createPageStream-int-}
```
public abstract OutputStream createPageStream(int pageNumber)
```


Method to create output page preview stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |

**Returns:**
java.io.OutputStream
### closePageStream(int pageNumber, OutputStream pageStream) {#closePageStream-int-java.io.OutputStream-}
```
public abstract void closePageStream(int pageNumber, OutputStream pageStream)
```


Method to release output page preview stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int |  |
| pageStream | java.io.OutputStream |  |

