---
title: "PageInfo"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Sayfa açıklama özelliklerini tanımlar."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.merger.domain.result/pageinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.result.IPageInfo](../../com.groupdocs.merger.domain.result/ipageinfo)
```
public class PageInfo implements IPageInfo
```

Sayfa açıklama özelliklerini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageInfo(int number, boolean visible)](#PageInfo-int-boolean-) | Yeni bir [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) sınıfının örneğini başlatır. |
| [PageInfo(int number, boolean visible, int width, int height)](#PageInfo-int-boolean-int-int-) | Yeni bir [PageInfo](../../com.groupdocs.merger.domain.result/pageinfo) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDocument()](#getDocument--) | Belge bilgisini alır. |
| [setDocument(DocumentInfo value)](#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-) | Belge bilgisini alır. |
| [getNumber()](#getNumber--) | Sayfa numarasını alır. |
| [getVisible()](#getVisible--) | Sayfanın görünür olup olmadığını gösterir. |
| [getWidth()](#getWidth--) | Sayfa genişliğini, görüntüye dönüştürüldüğünde piksel cinsinden alır. |
| [getHeight()](#getHeight--) | Sayfa yüksekliğini, görüntüye dönüştürüldüğünde piksel cinsinden alır. |
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
| genişlik | int | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden genişliği. |
| yükseklik | int | JPG veya PNG olarak görüntülendiğinde sayfanın piksel cinsinden yüksekliği. |

### getDocument() {#getDocument--}
```
public final DocumentInfo getDocument()
```


Belge bilgisini alır.

**Returns:**
[DocumentInfo](../../com.groupdocs.merger.domain.result/documentinfo)
### setDocument(DocumentInfo value) {#setDocument-com.groupdocs.merger.domain.result.DocumentInfo-}
```
public final void setDocument(DocumentInfo value)
```


Belge bilgisini alır.

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


Sayfa genişliğini, görüntüye dönüştürüldüğünde piksel cinsinden alır.

**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Sayfa yüksekliğini, görüntüye dönüştürüldüğünde piksel cinsinden alır.

**Returns:**
int
