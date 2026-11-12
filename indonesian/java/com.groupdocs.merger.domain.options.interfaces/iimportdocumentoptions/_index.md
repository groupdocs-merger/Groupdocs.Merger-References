---
title: "IImportDocumentOptions"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Antarmuka untuk impor dokumen tersemat."
type: docs
weight: 13
url: /id/java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface IImportDocumentOptions extends IOptions
```

Antarmuka untuk impor dokumen tersemat.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getObjectData()](#getObjectData--) | Data objek yang disematkan. |
| [getExtension()](#getExtension--) | Ekstensi objek yang disematkan. |
| [getPageNumber()](#getPageNumber--) | Nomor halaman untuk menyisipkan objek yang disematkan. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Data objek yang disematkan.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Ekstensi objek yang disematkan.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Nomor halaman untuk menyisipkan objek yang disematkan.

**Returns:**
int
