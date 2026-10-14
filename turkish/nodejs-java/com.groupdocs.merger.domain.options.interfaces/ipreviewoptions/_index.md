---
title: "IPreviewOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Ön izleme seçenekleri için arabirim."
type: docs
weight: 28
url: /tr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/ipreviewoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface IPreviewOptions extends IPageOptions
```

Ön izleme seçenekleri için arabirim.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Önizleme genişliği. |
| [setWidth(int value)](#setWidth-int-) | Önizleme genişliği. |
| [getHeight()](#getHeight--) | Önizleme yüksekliği. |
| [setHeight(int value)](#setHeight-int-) | Önizleme yüksekliği. |
| [getResolution()](#getResolution--) | Görüntü çözünürlüğü. |
| [setResolution(int value)](#setResolution-int-) | Görüntü çözünürlüğü. |
| [getMode()](#getMode--) | Önizleme modu alınır. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Bölme seçeneklerini doğrular. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Sayfa numarasına göre tanımlı uzantıyla önizlenen belgenin tam dosya yolunu alır. |
| [getPageStreamFactory()](#getPageStreamFactory--) | Çıktı sayfa önizleme akışını oluşturmak için yöntemi tanımlayan delege. |
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Önizleme genişliği.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public abstract void setWidth(int value)
```


Önizleme genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Önizleme yüksekliği.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public abstract void setHeight(int value)
```


Önizleme yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public abstract int getResolution()
```


Görüntü çözünürlüğü.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public abstract void setResolution(int value)
```


Görüntü çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public abstract int getMode()
```


Önizleme modu alınır.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Bölme seçeneklerini doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Sınıfın [FileType](../../com.groupdocs.merger.domain/filetype) dosya türü. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public abstract String getPathByPageNumber(int pageNumber, String extension)
```


Sayfa numarasına göre tanımlı uzantıyla önizlenen belgenin tam dosya yolunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumber | int | Önizleme sayfa numarası. |
| uzantı | java.lang.String | Dosyanın uzantısı. |

**Returns:**
java.lang.String - Tam dosya yolu.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public abstract PageStreamFactory getPageStreamFactory()
```


Çıktı sayfa önizleme akışını oluşturmak için yöntemi tanımlayan delege.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
