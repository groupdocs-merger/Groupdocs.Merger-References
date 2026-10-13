---
title: "OrientationOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Sayfa yönü için seçenekler sağlar."
type: docs
weight: 23
url: /tr/java/com.groupdocs.merger.domain.options/orientationoptions/
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
| [OrientationOptions(int orientationMode)](#OrientationOptions-int-) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır. |
| [OrientationOptions(int orientationMode, int[] pageNumbers)](#OrientationOptions-int-int---) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber)](#OrientationOptions-int-int-int-) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır. |
| [OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)](#OrientationOptions-int-int-int-int-) | Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Sayfa yönlendirmesi için modu alır. |
### OrientationOptions(int orientationMode) {#OrientationOptions-int-}
```
public OrientationOptions(int orientationMode)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) yönlendirme modu. |

### OrientationOptions(int orientationMode, int[] pageNumbers) {#OrientationOptions-int-int---}
```
public OrientationOptions(int orientationMode, int[] pageNumbers)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) yönlendirme modu. |
| pageNumbers | int[] | Sayfa numaraları. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber) {#OrientationOptions-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) yönlendirme modu. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode) {#OrientationOptions-int-int-int-int-}
```
public OrientationOptions(int orientationMode, int startNumber, int endNumber, int mode)
```


Yeni bir [OrientationOptions](../../com.groupdocs.merger.domain.options/orientationoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orientationMode | int | [OrientationMode](../../com.groupdocs.merger.domain.options/orientationmode) yönlendirme modu. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### getMode() {#getMode--}
```
public final int getMode()
```


Sayfa yönlendirmesi için modu alır.

**Returns:**
int
