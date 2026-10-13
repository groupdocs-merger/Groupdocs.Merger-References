---
title: "OleDiagramOptions"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Menyediakan opsi untuk mengimpor dokumen tertanam ke Diagram melalui OLE."
type: docs
weight: 18
url: /id/java/com.groupdocs.merger.domain.options/olediagramoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleDiagramOptions](../../com.groupdocs.merger.domain.options.interfaces/iolediagramoptions)
```
public class OleDiagramOptions extends ImportDocumentOptions implements IOleDiagramOptions
```

Menyediakan opsi untuk mengimpor dokumen tertanam ke Diagram melalui OLE.

--------------------

**Learn more**

 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleDiagramOptions-byte---byte---java.lang.String-int-) | Menginisialisasi instance baru dari kelas [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)](#OleDiagramOptions-java.lang.String-byte---int-) | Menginisialisasi instance baru dari kelas [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
| [OleDiagramOptions(String filePath, int pageNumber)](#OleDiagramOptions-java.lang.String-int-) | Menginisialisasi instance baru dari kelas [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getX()](#getX--) | Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [setX(int value)](#setX-int-) | Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [getY()](#getY--) | Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [setY(int value)](#setY-int-) | Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman. |
| [getWidth()](#getWidth--) | Lebar bentuk objek tertanam dalam inci. |
| [setWidth(int value)](#setWidth-int-) | Lebar bentuk objek tertanam dalam inci. |
| [getHeight()](#getHeight--) | Tinggi bentuk objek tertanam dalam inci. |
| [setHeight(int value)](#setHeight-int-) | Tinggi bentuk objek tertanam dalam inci. |
| [getImageData()](#getImageData--) | Data gambar dari objek yang disematkan. |
### OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleDiagramOptions-byte---byte---java.lang.String-int-}
```
public OleDiagramOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objectData | byte[] | Data objek yang disematkan. |
| imageData | byte[] | Data gambar dari objek yang disematkan. |
| ekstensi | java.lang.String | Ekstensi objek yang disematkan. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### OleDiagramOptions(String filePath, byte[] imageData, int pageNumber) {#OleDiagramOptions-java.lang.String-byte---int-}
```
public OleDiagramOptions(String filePath, byte[] imageData, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| imageData | byte[] | Data gambar dari objek yang disematkan. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### OleDiagramOptions(String filePath, int pageNumber) {#OleDiagramOptions-java.lang.String-int-}
```
public OleDiagramOptions(String filePath, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OleDiagramOptions](../../com.groupdocs.merger.domain.options/olediagramoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### getX() {#getX--}
```
public final int getX()
```


Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Koordinat X dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getY() {#getY--}
```
public final int getY()
```


Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Koordinat Y dari pin bentuk objek yang disematkan (pusat rotasi) relatif terhadap halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar bentuk objek tertanam dalam inci.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar bentuk objek tertanam dalam inci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi bentuk objek tertanam dalam inci.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi bentuk objek tertanam dalam inci.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Data gambar dari objek yang disematkan.

**Returns:**
byte[]
