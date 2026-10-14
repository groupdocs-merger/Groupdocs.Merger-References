---
title: "IOleDiagramOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Antarmuka untuk opsi impor dokumen tersemat ke Diagram melalui OLE."
type: docs
weight: 17
url: /id/nodejs-java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions), [com.groupdocs.merger.domain.options.interfaces.ISizeOptions](../../com.groupdocs.merger.domain.options.interfaces/isizeoptions)
```
public interface IOleDiagramOptions extends IImportDocumentOptions, ISizeOptions
```

Antarmuka untuk opsi impor dokumen tersemat ke Diagram melalui OLE.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getX()](#getX--) | Koordinat X pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman. |
| [setX(int value)](#setX-int-) | Koordinat X pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman. |
| [getY()](#getY--) | Koordinat Y pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman. |
| [setY(int value)](#setY-int-) | Koordinat Y pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman. |
| [getImageData()](#getImageData--) | Data gambar objek tersemat. |
### getX() {#getX--}
```
public abstract int getX()
```


Koordinat X pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


Koordinat X pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Koordinat Y pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Koordinat Y pin bentuk objek tersemat (pusat rotasi) relatif terhadap halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Data gambar objek tersemat.

**Returns:**
byte[]
