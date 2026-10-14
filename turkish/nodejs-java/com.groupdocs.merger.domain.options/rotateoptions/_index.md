---
title: "RotateOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Sayfa döndürme için seçenekler sağlar."
type: docs
weight: 33
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/rotateoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions)
```
public class RotateOptions extends PageOptions implements IRotateOptions
```

Sayfa döndürme için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RotateOptions(int rotateMode)](#RotateOptions-int-) | Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır. |
| [RotateOptions(int rotateMode, int[] pageNumbers)](#RotateOptions-int-int---) | Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber)](#RotateOptions-int-int-int-) | Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır. |
| [RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)](#RotateOptions-int-int-int-int-) | Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Döndürme modu alınır (90, 180 veya 270 derece). |
### RotateOptions(int rotateMode) {#RotateOptions-int-}
```
public RotateOptions(int rotateMode)
```


Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateMode | int | Modun döndürme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |

### RotateOptions(int rotateMode, int[] pageNumbers) {#RotateOptions-int-int---}
```
public RotateOptions(int rotateMode, int[] pageNumbers)
```


Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateMode | int | Modun döndürme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Sayfa numaraları. |

### RotateOptions(int rotateMode, int startNumber, int endNumber) {#RotateOptions-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber)
```


Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateMode | int | Modun döndürme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |

### RotateOptions(int rotateMode, int startNumber, int endNumber, int mode) {#RotateOptions-int-int-int-int-}
```
public RotateOptions(int rotateMode, int startNumber, int endNumber, int mode)
```


Yeni bir [RotateOptions](../../com.groupdocs.merger.domain.options/rotateoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateMode | int | Modun döndürme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |
| mode | int | Aralık modu. |

### getMode() {#getMode--}
```
public final int getMode()
```


Döndürme modu alınır (90, 180 veya 270 derece).

**Returns:**
int
