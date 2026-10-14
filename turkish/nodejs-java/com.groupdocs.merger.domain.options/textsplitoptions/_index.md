---
title: "TextSplitOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Belge metin bölme için seçenekler sağlar."
type: docs
weight: 39
url: /tr/nodejs-java/com.groupdocs.merger.domain.options/textsplitoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions)
```
public class TextSplitOptions implements ITextSplitOptions
```

Belge metin bölme için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextSplitOptions(int[] lineNumbers)](#TextSplitOptions-int---) | Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır. |
| [TextSplitOptions(int mode, int[] lineNumbers)](#TextSplitOptions-int-int---) | Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır. |
| [TextSplitOptions(String filePathFormat, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int---) | Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır. |
| [TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)](#TextSplitOptions-java.lang.String-int-int---) | Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---) | Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır. |
| [TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)](#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---) | Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Metin bölme modu. |
| [getLineNumbers()](#getLineNumbers--) | Metin bölme için satır numaraları. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Bölme seçeneklerini doğrular. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Tanımlı uzantıyla indeksine göre bölünmüş belgenin tam dosya yolunu alır. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Çıktı sayfa önizleme akışını oluşturmak veya serbest bırakmak için SplitStreamFactory. |
### TextSplitOptions(int[] lineNumbers) {#TextSplitOptions-int---}
```
public TextSplitOptions(int[] lineNumbers)
```


Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lineNumbers | int[] | Metin bölme için satır numaraları. |

### TextSplitOptions(int mode, int[] lineNumbers) {#TextSplitOptions-int-int---}
```
public TextSplitOptions(int mode, int[] lineNumbers)
```


Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | int | Metin bölme modu. |
| lineNumbers | int[] | Metin bölme için satır numaraları. |

### TextSplitOptions(String filePathFormat, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int---}
```
public TextSplitOptions(String filePathFormat, int[] lineNumbers)
```


Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu biçimi, örneğin 'c:/split\{0\}.doc' veya 'c:/split\{0\}.\{1\}' gibi, önceden tanımlı uzantı ile. |
| lineNumbers | int[] | Metin bölme için satır numaraları. |

### TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers) {#TextSplitOptions-java.lang.String-int-int---}
```
public TextSplitOptions(String filePathFormat, int mode, int[] lineNumbers)
```


Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePathFormat | java.lang.String | Dosya yolu biçimi, örneğin 'c:/split\{0\}.doc' veya 'c:/split\{0\}.\{1\}' gibi, önceden tanımlı uzantı ile. |
| mode | int | Metin bölme modu. |
| lineNumbers | int[] | Metin bölme için satır numaraları. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int[] lineNumbers)
```


Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı oluşturan yöntem. |
| lineNumbers | int[] | Metin bölme için satır numaraları. |

### TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers) {#TextSplitOptions-com.groupdocs.merger.domain.common.SplitStreamFactory-int-int---}
```
public TextSplitOptions(SplitStreamFactory splitStreamFactory, int mode, int[] lineNumbers)
```


Yeni bir [TextSplitOptions](../../com.groupdocs.merger.domain.options/textsplitoptions) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| splitStreamFactory | [SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory) | Çıktı bölünmüş verileri yazmak için kullanılan akışı oluşturan yöntem. |
| mode | int | Metin bölme modu. |
| lineNumbers | int[] | Metin bölme için satır numaraları. |

### getMode() {#getMode--}
```
public final int getMode()
```


Metin bölme modu.

**Returns:**
int
### getLineNumbers() {#getLineNumbers--}
```
public final int[] getLineNumbers()
```


Metin bölme için satır numaraları.

**Returns:**
int[]
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Bölme seçeneklerini doğrular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Sınıfın [FileType](../../com.groupdocs.merger.domain/filetype) dosya türü. |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public final String getPathByIndex(int index, String extension)
```


Tanımlı uzantıyla indeksine göre bölünmüş belgenin tam dosya yolunu alır.

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
