---
title: "ISplitOptions"
second_title: "GroupDocs.Merger Node.js için Java API Referansı"
description: "Bölme seçenekleri için arayüz."
type: docs
weight: 33
url: /tr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Bölme seçenekleri için arayüz.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMode()](#getMode--) | Sayfa bölme için modu alır. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Bölme seçeneklerini doğrular. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Tanımlı uzantıyla indeksine göre bölünmüş belgenin tam dosya yolunu alır. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Çıktı bölme akışı oluşturmak için yöntemi tanımlayan temsilci. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Sayfa bölme için modu alır.

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

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
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
public abstract SplitStreamFactory getSplitStreamFactory()
```


Çıktı bölme akışı oluşturmak için yöntemi tanımlayan temsilci.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
