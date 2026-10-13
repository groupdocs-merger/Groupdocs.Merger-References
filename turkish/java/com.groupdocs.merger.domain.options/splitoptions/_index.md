---
title: "SplitOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Belge sayfa bölme için seçenekler sağlar."
type: docs
weight: 38
url: /tr/java/com.groupdocs.merger.domain.options/splitoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions)
```
public class SplitOptions extends PageOptions implements ISplitOptions
```

Belge sayfa bölme için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SplitOptions(int[] pageNumbers, int splitMode)](#SplitOptions-int---int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(int splitMode, int startNumber, int endNumber)](#SplitOptions-int-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-int-int-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(String filePathFormat, int[] pageNumbers)](#SplitOptions-java.lang.String-int---) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)](#SplitOptions-java.lang.String-int---int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)](#SplitOptions-java.lang.String-int-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)](#SplitOptions-java.lang.String-int-int-java.lang.Integer-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-java.lang.String-int-int-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
| [SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)](#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-) | Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Sayfa bölme için modu alır. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Bölme seçeneklerini doğrular. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Önceden tanımlı uzantıyla, indeksine göre bölünmüş belgenin tam dosya yolunu alır. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Çıktı sayfa önizleme akışını oluşturmak veya serbest bırakmak için SplitStreamFactory. |
### SplitOptions(int[] pageNumbers, int splitMode) {#SplitOptions-int---int-}
```
public SplitOptions(int[] pageNumbers, int splitMode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageNumbers | int[] | Sayfa numaraları. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(int splitMode, int startNumber, int endNumber) {#SplitOptions-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### SplitOptions(int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-int-int-int-int-}
```
public SplitOptions(int splitMode, int startNumber, int endNumber, int mode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### SplitOptions(String filePathFormat, int[] pageNumbers) {#SplitOptions-java.lang.String-int---}
```
public SplitOptions(String filePathFormat, int[] pageNumbers)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu formatı örn. 'c:/split\\{0\\}.doc' veya 'c:/split\\{0\\}.\\{1\\}' zaten önceden tanımlı uzantıyla. |
| pageNumbers | int[] | Sayfa numaraları. |

### SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode) {#SplitOptions-java.lang.String-int---int-}
```
public SplitOptions(String filePathFormat, int[] pageNumbers, int splitMode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu formatı örn. 'c:/split\\{0\\}.doc' veya 'c:/split\\{0\\}.\\{1\\}' zaten önceden tanımlı uzantıyla. |
| pageNumbers | int[] | Sayfa numaraları. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(String filePathFormat, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu formatı örn. 'c:/split\\{0\\}.doc' veya 'c:/split\\{0\\}.\\{1\\}' zaten önceden tanımlı uzantıyla. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber) {#SplitOptions-java.lang.String-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu formatı örn. 'c:/split\\{0\\}.doc' veya 'c:/split\\{0\\}.\\{1\\}' zaten önceden tanımlı uzantıyla. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode) {#SplitOptions-java.lang.String-int-int-java.lang.Integer-}
```
public SplitOptions(String filePathFormat, int startNumber, int endNumber, Integer mode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu formatı örn. 'c:/split\\{0\\}.doc' veya 'c:/split\\{0\\}.\\{1\\}' zaten önceden tanımlı uzantıyla. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | java.lang.Integer | Aralık modu. |

### SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-java.lang.String-int-int-int-int-}
```
public SplitOptions(String filePathFormat, int splitMode, int startNumber, int endNumber, int mode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu formatı örn. 'c:/split\\{0\\}.doc' veya 'c:/split\\{0\\}.\\{1\\}' zaten önceden tanımlı uzantıyla. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### SplitOptions(SplitStreamFactory splitStreamFactory) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |
| pageNumbers | int[] | Sayfa numaraları. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int[] pageNumbers, int splitMode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |
| pageNumbers | int[] | Sayfa numaraları. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-java.lang.Integer-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int startNumber, int endNumber, Integer mode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | java.lang.Integer | Aralık modu. |

### SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode) {#SplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int-int-int-}
```
public SplitOptions(SplitStreamFactory splitStreamFactory, int splitMode, int startNumber, int endNumber, int mode)
```


Yeni bir [SplitOptions](../../com.groupdocs.merger.domain.options/splitoptions) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı örnekleyen yöntem. |
| splitMode | int | Bölme modu (\\#getMode.getMode/\\#setMode(int).setMode(int)). |
| startNumber | int | Başlangıç sayfa numarası. |
| endNumber | int | Son sayfa numarası. |
| mod | int | Aralık modu. |

### getMode() {#getMode--}
```
public final int getMode()
```


Sayfa bölme için modu alır.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Bölme seçeneklerini doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Dosya türü, [FileType](../../com.groupdocs.merger.domain/filetype) sınıfının. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Önceden tanımlı uzantıyla, indeksine göre bölünmüş belgenin tam dosya yolunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| indeks | int | Bölünmüş belgenin indeksi. |
| uzantı | java.lang.String | Dosyanın uzantısı. |

**Returns:**
java.lang.String - Tam dosya yolu.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public SplitStreamFactory getSplitStreamFactory()
```


Çıktı sayfa önizleme akışını oluşturmak veya serbest bırakmak için SplitStreamFactory.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
