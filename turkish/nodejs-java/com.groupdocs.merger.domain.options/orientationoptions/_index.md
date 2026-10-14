---
title: "OrientationOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Sayfa yönü için seçenekler sağlar."
type: docs
weight: 23
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/orientationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions)
```
public class OrientationOptions extends PageOptions implements IOrientationOptions
```

Sayfa yönü için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır. |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Sayfa yönlendirmesi için modu alır. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | Yönlendirme modu [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | Yönlendirme modu [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| pageNumbers | int[] | Sayfa numaraları. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | Yönlendirme modu [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | Yönlendirme modu [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |
| mode | int | Aralık modu. |

### getMode() {#getMode--}
```
public final int getMode()
```


Sayfa yönlendirmesi için modu alır.

**Returns:**
int
