---
title: "ILoadOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk opsi pemuatan dokumen."
type: docs
weight: 15
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iloadoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ILoadOptions extends IOptions
```

Antarmuka untuk opsi pemuatan dokumen.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getType()](#getType--) | Jenis file yang akan dibuka. |
| [getPassword()](#getPassword--) | Kata sandi untuk membuka file yang dilindungi kata sandi. |
| [getExtension()](#getExtension--) | Ekstensi file yang akan dibuka. |
| [getEncoding()](#getEncoding--) | Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). |
### getType() {#getType--}
```
public abstract FileType getType()
```


Jenis file yang akan dibuka.

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Kata sandi untuk membuka file yang dilindungi kata sandi.

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public abstract String getExtension()
```


Ekstensi file yang akan dibuka.

**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public abstract Charset getEncoding()
```


Pengkodean yang digunakan saat membuka file berbasis teks seperti [FileType.CSV](../../com.groupdocs.merger.domain/filetype\#CSV) atau [FileType.TXT](../../com.groupdocs.merger.domain/filetype\#TXT). Nilai default adalah [DefaultCharset][].


[DefaultCharset]: https://docs.oracle.com/javase/7/docs/api/java/nio/charset/Charset.html#defaultCharset%28%29

**Returns:**
java.nio.charset.Charset
