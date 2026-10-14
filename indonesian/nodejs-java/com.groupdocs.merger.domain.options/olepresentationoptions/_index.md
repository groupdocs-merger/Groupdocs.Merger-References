---
title: "OlePresentationOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk mengimpor dokumen tersemat ke Presentasi melalui OLE."
type: docs
weight: 19
url: /id/nodejs-java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Menyediakan opsi untuk mengimpor dokumen tersemat ke Presentasi melalui OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Menginisialisasi instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Menginisialisasi instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getX()](#getX--) | Koordinat X dari bingkai objek tersemat. |
| [setX(int value)](#setX-int-) | Koordinat X dari bingkai objek tersemat. |
| [getY()](#getY--) | Koordinat Y dari bingkai objek tersemat. |
| [setY(int value)](#setY-int-) | Koordinat Y dari bingkai objek tersemat. |
| [getWidth()](#getWidth--) | Lebar bingkai objek yang disematkan. |
| [setWidth(int value)](#setWidth-int-) | Lebar bingkai objek yang disematkan. |
| [getHeight()](#getHeight--) | Tinggi bingkai objek yang disematkan. |
| [setHeight(int value)](#setHeight-int-) | Tinggi bingkai objek yang disematkan. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objectData | byte[] | Data objek tersemat. |
| ekstensi | java.lang.String | Ekstensi objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Menginisialisasi instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### getX() {#getX--}
```
public final int getX()
```


Koordinat X dari bingkai objek tersemat.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Koordinat X dari bingkai objek tersemat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getY() {#getY--}
```
public final int getY()
```


Koordinat Y dari bingkai objek tersemat.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Koordinat Y dari bingkai objek tersemat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar bingkai objek yang disematkan.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar bingkai objek yang disematkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi bingkai objek yang disematkan.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi bingkai objek yang disematkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

