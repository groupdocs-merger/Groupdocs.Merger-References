---
title: "IOleDiagramOptions"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Antarmuka untuk opsi impor dokumen tersemat ke Diagram melalui OLE."
type: docs
weight: 17
url: /id/java/com.groupdocs.merger.domain.options.interfaces/iolediagramoptions/
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
| [getX()](#getX--) | Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [setX(int value)](#setX-int-) | Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [getY()](#getY--) | Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [setY(int value)](#setY-int-) | Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [getImageData()](#getImageData--) | Data gambar dari objek yang disematkan. |
### getX() {#getX--}
```
public abstract int getX()
```


Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public abstract void setX(int value)
```


Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getY() {#getY--}
```
public abstract int getY()
```


Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public abstract void setY(int value)
```


Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getImageData() {#getImageData--}
```
public abstract byte[] getImageData()
```


Data gambar dari objek yang disematkan.

**Returns:**
byte[]
