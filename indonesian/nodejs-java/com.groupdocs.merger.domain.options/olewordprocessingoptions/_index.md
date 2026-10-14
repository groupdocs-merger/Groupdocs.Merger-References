---
title: "OleWordProcessingOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk mengimpor dokumen tersemat ke Pengolahan Kata melalui OLE."
type: docs
weight: 21
url: /id/nodejs-java/com.groupdocs.merger.domain.options/olewordprocessingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOleWordProcessingOptions](../../com.groupdocs.merger.domain.options.interfaces/iolewordprocessingoptions)
```
public class OleWordProcessingOptions extends ImportDocumentOptions implements IOleWordProcessingOptions
```

Menyediakan opsi untuk mengimpor dokumen tersemat ke Pengolahan Kata melalui OLE.

--------------------

**Learn more**

 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]


[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)](#OleWordProcessingOptions-byte---byte---java.lang.String-int-) | Menginisialisasi instance baru dari kelas [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)](#OleWordProcessingOptions-java.lang.String-byte---int-) | Menginisialisasi instance baru dari kelas [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
| [OleWordProcessingOptions(String filePath, int pageNumber)](#OleWordProcessingOptions-java.lang.String-int-) | Menginisialisasi instance baru dari kelas [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLeft()](#getLeft--) | Koordinat kiri gambar objek Ole. |
| [setLeft(int value)](#setLeft-int-) | Koordinat kiri gambar objek Ole. |
| [getTop()](#getTop--) | Koordinat atas gambar objek Ole. |
| [setTop(int value)](#setTop-int-) | Koordinat atas gambar objek Ole. |
| [getWidth()](#getWidth--) | Lebar gambar objek Ole. |
| [setWidth(int value)](#setWidth-int-) | Lebar gambar objek Ole. |
| [getHeight()](#getHeight--) | Tinggi gambar objek Ole. |
| [setHeight(int value)](#setHeight-int-) | Tinggi gambar objek Ole. |
| [getImageData()](#getImageData--) | Data gambar objek Ole. |
### OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber) {#OleWordProcessingOptions-byte---byte---java.lang.String-int-}
```
public OleWordProcessingOptions(byte[] objectData, byte[] imageData, String extension, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objectData | byte[] | Data objek tersemat. |
| imageData | byte[] | Data gambar objek tersemat. |
| ekstensi | java.lang.String | Ekstensi objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber) {#OleWordProcessingOptions-java.lang.String-byte---int-}
```
public OleWordProcessingOptions(String filePath, byte[] imageData, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| imageData | byte[] | Data gambar objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### OleWordProcessingOptions(String filePath, int pageNumber) {#OleWordProcessingOptions-java.lang.String-int-}
```
public OleWordProcessingOptions(String filePath, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OleWordProcessingOptions](../../com.groupdocs.merger.domain.options/olewordprocessingoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Koordinat kiri gambar objek Ole.

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Koordinat kiri gambar objek Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Koordinat atas gambar objek Ole.

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Koordinat atas gambar objek Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar gambar objek Ole.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar gambar objek Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi gambar objek Ole.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi gambar objek Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Data gambar objek Ole.

**Returns:**
byte[]
