---
title: "IImportDocumentOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk impor dokumen tersemat."
type: docs
weight: 13
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions/
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
| [getObjectData()](#getObjectData--) | Data objek tersemat. |
| [getExtension()](#getExtension--) | Ekstensi objek tersemat. |
| [getPageNumber()](#getPageNumber--) | Nomor halaman untuk menyisipkan objek tersemat. |
### getObjectData() {#getObjectData--}
```
public abstract byte[] getObjectData()
```


Data objek tersemat.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Ekstensi objek tersemat.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Nomor halaman untuk menyisipkan objek tersemat.

**Returns:**
int
