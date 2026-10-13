---
title: "PageInfo"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Sayfa tanım özelliklerini tanımlar."
type: docs
weight: 11
url: /tr/java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Sayfa tanım özelliklerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Yeni bir [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) sınıfının örneğini başlatır. |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Yeni bir [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDocument()](#getDocument--) | Belge bilgilerini alır. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Belge bilgilerini alır. |
| [getNumber()](#getNumber--) | Sayfa numarasını alır. |
| [getVisible()](#getVisible--) | Sayfanın görünür olup olmadığını gösterir. |
| [getWidth()](#getWidth--) | Sayfanın görüntüye dönüştürüldüğünde piksel cinsinden genişliğini alır. |
| [getHeight()](#getHeight--) | Sayfanın görüntüye dönüştürüldüğünde piksel cinsinden yüksekliğini alır. |
### PageInfo(int number, boolean visible) {#PageInfo-int-boolean-}
```
public PageInfo(int number, boolean visible)
```


Yeni bir [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| görünür | boolean | Sayfa görünürlük göstergesi. |

### PageInfo(int number, boolean visible, int width, int height) {#PageInfo-int-boolean-int-int-}
```
public PageInfo(int number, boolean visible, int width, int height)
```


Yeni bir [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayı | int | Sayfa numarası. |
| görünür | boolean | Sayfa görünürlük göstergesi. |
| genişlik | int | Sayfanın JPG veya PNG olarak görüntülendiğinde piksel cinsinden genişliği. |
| yükseklik | int | Sayfanın JPG veya PNG olarak görüntülendiğinde piksel cinsinden yüksekliği. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Belge bilgilerini alır.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Belge bilgilerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo) |  |

### getNumber() {#getNumber--}
```
public final int getNumber()
```


Sayfa numarasını alır.

**Returns:**
int
### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Sayfanın görünür olup olmadığını gösterir.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Sayfanın görüntüye dönüştürüldüğünde piksel cinsinden genişliğini alır.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Sayfanın görüntüye dönüştürüldüğünde piksel cinsinden yüksekliğini alır.

**Returns:**
int
