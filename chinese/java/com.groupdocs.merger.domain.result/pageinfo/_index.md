---
title: "PageInfo"
second_title: "GroupDocs.Merger 适用于 Java 的 API 参考"
description: "定义页面描述属性。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

定义页面描述属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | 初始化 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 类的新实例。 |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | 初始化 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDocument()](#getDocument--) | 获取文档信息。 |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | 获取文档信息。 |
| [getNumber()](#getNumber--) | 获取页码。 |
| [getVisible()](#getVisible--) | 指示页面是否可见。 |
| [getWidth()](#getWidth--) | 获取转换为图像时的页面宽度（像素）。 |
| [getHeight()](#getHeight--) | 获取转换为图像时的页面高度（像素）。 |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


初始化 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 编号 | int | 页码。 |
| 可见 | boolean | 页面可见性指示器。 |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


初始化 [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 编号 | int | 页码。 |
| 可见 | boolean | 页面可见性指示器。 |
| 宽度 | int | 以 JPG 或 PNG 查看时，页面的宽度（像素）。 |
| 高度 | int | 以 JPG 或 PNG 查看时，页面的高度（像素）。 |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


获取文档信息。

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


获取文档信息。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


获取页码。

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


指示页面是否可见。

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取转换为图像时的页面宽度（像素）。

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取转换为图像时的页面高度（像素）。

**Returns:**
int
