---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger için Java API Referansı"
description: "Gömülü belgenin içe aktarımı için arabirim."
type: docs
weight: 13
url: /tr/java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Gömülü belgenin içe aktarımı için arabirim.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getObjectData()](#getObjectData--) | Gömülü nesnenin verileri. |
| [getExtension()](#getExtension--) | Gömülü nesnenin uzantısı. |
| [getPageNumber()](#getPageNumber--) | Gömülü nesnenin eklenmesi için sayfa numarası. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Gömülü nesnenin verileri.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Gömülü nesnenin uzantısı.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Gömülü nesnenin eklenmesi için sayfa numarası.

**Returns:**
int
