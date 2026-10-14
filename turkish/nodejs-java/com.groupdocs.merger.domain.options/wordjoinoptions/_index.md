---
title: "WordJoinOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Word birleştirme seçenekleri."
type: docs
weight: 43
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/wordjoinoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions), [com.groupdocs.merger.domain.options.PageJoinOptions](../../com.groupdocs.merger.domain.options/pagejoinoptions)
```
public class WordJoinOptions extends PageJoinOptions
```

Word birleştirme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordJoinOptions()](#WordJoinOptions--) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(int[] pageNumbers)](#WordJoinOptions-int---) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(int startNumber, int endNumber)](#WordJoinOptions-int-int-) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(int startNumber, int endNumber, int mode)](#WordJoinOptions-int-int-int-) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(FileType fileType)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(FileType fileType, int[] pageNumbers)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
| [WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)](#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-) | Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Word birleştirme modu. |
| [setMode(int value)](#setMode-int-) | Word birleştirme modu. |
| [getCompliance()](#getCompliance--) | Word Ooxml formatı için uyumluluk modu |
| [setCompliance(int value)](#setCompliance-int-) | Word Ooxml formatı için uyumluluk modu |
### WordJoinOptions() {#WordJoinOptions--}
```
public WordJoinOptions()
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

### WordJoinOptions(int[] pageNumbers) {#WordJoinOptions-int---}
```
public WordJoinOptions(int[] pageNumbers)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumbers | int[] | Sayfa numaraları. |

### WordJoinOptions(int startNumber, int endNumber) {#WordJoinOptions-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |

### WordJoinOptions(int startNumber, int endNumber, int mode) {#WordJoinOptions-int-int-int-}
```
public WordJoinOptions(int startNumber, int endNumber, int mode)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |
| mode | int | Aralık modu. |

### WordJoinOptions(FileType fileType) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-}
```
public WordJoinOptions(FileType fileType)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |

### WordJoinOptions(FileType fileType, int[] pageNumbers) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int---}
```
public WordJoinOptions(FileType fileType, int[] pageNumbers)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |
| pageNumbers | int[] | Sayfa numaraları. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |

### WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode) {#WordJoinOptions-com.groupdocs.merger.domain.FileType-int-int-int-}
```
public WordJoinOptions(FileType fileType, int startNumber, int endNumber, int mode)
```


Yeni bir [WordJoinOptions](../../com.groupdocs.merger.domain.options/wordjoinoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Birleştirilecek dosyanın türü. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Bitiş sayfa numarası. |
| mode | int | Aralık modu. |

### getMode() {#getMode--}
```
public final int getMode()
```


Word birleştirme modu.

**Returns:**
int
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Word birleştirme modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


Word Ooxml formatı için uyumluluk modu

**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


Word Ooxml formatı için uyumluluk modu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

