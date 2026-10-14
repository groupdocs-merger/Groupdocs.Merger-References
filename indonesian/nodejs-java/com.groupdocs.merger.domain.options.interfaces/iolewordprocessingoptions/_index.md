---
title: "IOleWordProcessingOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk opsi impor dokumen tersemat ke Pengolah Kata melalui OLE."
type: docs
weight: 20
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleWordProcessingOptions extends IImportDocumentOptions, ISizeOptions
```

Antarmuka untuk opsi impor dokumen tersemat ke Pengolah Kata melalui OLE.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLeft()](#getLeft--) | Koordinat kiri gambar objek Ole. |
| [setLeft(int value)](#setLeft-int-) | Koordinat kiri gambar objek Ole. |
| [getTop()](#getTop--) | Koordinat atas gambar objek Ole. |
| [setTop(int value)](#setTop-int-) | Koordinat atas gambar objek Ole. |
| [getImageData()](#getImageData--) | Data gambar objek Ole. |
### getLeft() {#getLeft--}
```
public abstract int getLeft()
```


Koordinat kiri gambar objek Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public abstract void setLeft(int value)
```


Koordinat kiri gambar objek Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public abstract int getTop()
```


Koordinat atas gambar objek Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public abstract void setTop(int value)
```


Koordinat atas gambar objek Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Data gambar objek Ole.

**Returns:**
byte[]
