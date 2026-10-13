---
title: "PageJoinOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Belge birleştirme için seçenekler sağlar."
type: docs
weight: 25
url: /tr/java/com.groupdocs.merger.domain.options/pagejoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions)
```
public class PageJoinOptions extends PageOptions implements IPageJoinOptions
```

Belge birleştirme için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PageJoinOptions()](#PageJoinOptions--) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(int[] pageNumbers)](#PageJoinOptions-int---) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(int startNumber, int endNumber)](#PageJoinOptions-int-int-) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(int startNumber, int endNumber, int mode)](#PageJoinOptions-int-int-int-) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(FileType fileType)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(FileType fileType, int[] pageNumbers)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
| [PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Birleştirilecek dosyanın türü. |
### PageJoinOptions() {#PageJoinOptions--}
```
public PageJoinOptions()
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

### PageJoinOptions(int[] pageNumbers) {#PageJoinOptions-int---}
```
public PageJoinOptions(int[] pageNumbers)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumbers | int[] | Sayfa numaraları. |

### PageJoinOptions(int startNumber, int endNumber) {#PageJoinOptions-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### PageJoinOptions(int startNumber, int endNumber, int mode) {#PageJoinOptions-int-int-int-}
```
public PageJoinOptions(int startNumber, int endNumber, int mode)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### PageJoinOptions(FileType fileType) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public PageJoinOptions(FileType fileType)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |

### PageJoinOptions(FileType fileType, int[] pageNumbers) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public PageJoinOptions(FileType fileType, int[] pageNumbers)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |
| pageNumbers | int[] | Sayfa numaraları. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#PageJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public PageJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Yeni bir [PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### getType() {#getType--}
```
public final FileType getType()
```


Birleştirilecek dosyanın türü.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
