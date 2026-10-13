---
title: "ImageJoinOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Görüntü birleştirme seçenekleri."
type: docs
weight: 13
url: /tr/java/com.groupdocs.merger.domain.options/imagejoinoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/iimagejoinoptions)
```
public class ImageJoinOptions implements IImageJoinOptions
```

Görüntü birleştirme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageJoinOptions()](#ImageJoinOptions--) | Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır. |
| [ImageJoinOptions(FileType fileType)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-) | Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır. |
| [ImageJoinOptions(int imageJoinMode)](#ImageJoinOptions-int-) | Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır. |
| [ImageJoinOptions(FileType fileType, int imageJoinMode)](#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-) | Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Görüntü dosya türü. |
| [getMode()](#getMode--) | Görüntü birleştirme modu. |
### ImageJoinOptions() {#ImageJoinOptions--}
```
public ImageJoinOptions()
```


Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır.

### ImageJoinOptions(FileType fileType) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public ImageJoinOptions(FileType fileType)
```


Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Görüntü dosya türü. |

### ImageJoinOptions(int imageJoinMode) {#ImageJoinOptions-int-}
```
public ImageJoinOptions(int imageJoinMode)
```


Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageJoinMode | int | Görüntü birleştirme modu. |

### ImageJoinOptions(FileType fileType, int imageJoinMode) {#ImageJoinOptions-com.groupdocs.merger.domain.FileType-int-}
```
public ImageJoinOptions(FileType fileType, int imageJoinMode)
```


Yeni bir [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) sınıfının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Görüntü dosya türü. |
| imageJoinMode | int | Görüntü birleştirme modu. |

### getType() {#getType--}
```
public final FileType getType()
```


Görüntü dosya türü.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getMode() {#getMode--}
```
public final int getMode()
```


Görüntü birleştirme modu.

**Returns:**
int
