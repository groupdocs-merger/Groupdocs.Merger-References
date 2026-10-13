---
title: "PreviewOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Belge önizleme seçeneklerini temsil eder."
type: docs
weight: 31
url: /tr/java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Belge önizleme seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır. |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Önizleme genişliği. |
| [setWidth(int value)](#setWidth-int-) | Önizleme genişliği. |
| [getHeight()](#getHeight--) | Önizleme yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Önizleme yüksekliği. |
| [getResolution()](#getResolution--) | Görüntü çözünürlüğü. |
| [setResolution(int value)](#setResolution-int-) | Görüntü çözünürlüğü. |
| [getMode()](#getMode--) | Önizleme için mod. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Önizleme seçeneklerini doğrular. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Sayfa numarası ve belirlenmiş uzantı ile önizlenen belgenin tam dosya yolunu alır. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Çıktı sayfa önizleme akışını oluşturmak veya serbest bırakmak için PageStreamFactory. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
| previewMode | int | Modun önizleme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
| previewMode | int | Modun önizleme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Sayfa numaraları. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
| previewMode | int | Modun önizleme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Yeni bir [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntem. |
| previewMode | int | Modun önizleme modu (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Önizleme genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Önizleme genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Önizleme yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Önizleme yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Görüntü çözünürlüğü.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Görüntü çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Önizleme için mod.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Önizleme seçeneklerini doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Dosya türü. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Sayfa numarası ve belirlenmiş uzantı ile önizlenen belgenin tam dosya yolunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | int | Önizleme sayfa numarası. |
| uzantı | java.lang.String | Dosyanın uzantısı. |

**Returns:**
java.lang.String - Tam dosya yolu.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


Çıktı sayfa önizleme akışını oluşturmak veya serbest bırakmak için PageStreamFactory.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
