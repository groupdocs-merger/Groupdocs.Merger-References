---
title: "OlePresentationOptions"
second_title: "GroupDocs.Merger untuk Java Referensi API"
description: "Menyediakan opsi untuk mengimpor dokumen tertanam ke Presentasi melalui OLE."
type: docs
weight: 19
url: /id/java/com.groupdocs.merger.domain.options/olepresentationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOlePresentationOptions](../../com.groupdocs.merger.domain.options.interfaces/iolepresentationoptions)
```
public class OlePresentationOptions extends ImportDocumentOptions implements IOlePresentationOptions
```

Menyediakan opsi untuk mengimpor dokumen tertanam ke Presentasi melalui OLE.

--------------------

**Learn more**

 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]


[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OlePresentationOptions(byte[] objectData, String extension, int pageNumber)](#OlePresentationOptions-byte---java.lang.String-int-) | Menginisialisasi sebuah instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
| [OlePresentationOptions(String filePath, int pageNumber)](#OlePresentationOptions-java.lang.String-int-) | Menginisialisasi sebuah instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getX()](#getX--) | Koordinat X dari bingkai objek tertanam. |
| [setX(int value)](#setX-int-) | Koordinat X dari bingkai objek tertanam. |
| [getY()](#getY--) | Koordinat Y dari bingkai objek tertanam. |
| [setY(int value)](#setY-int-) | Koordinat Y dari bingkai objek tertanam. |
| [getWidth()](#getWidth--) | Lebar bingkai objek tersemat. |
| [setWidth(int value)](#setWidth-int-) | Lebar bingkai objek tersemat. |
| [getHeight()](#getHeight--) | Tinggi bingkai objek tersemat. |
| [setHeight(int value)](#setHeight-int-) | Tinggi bingkai objek tersemat. |
### OlePresentationOptions(byte[] objectData, String extension, int pageNumber) {#OlePresentationOptions-byte---java.lang.String-int-}
```
public OlePresentationOptions(byte[] objectData, String extension, int pageNumber)
```


Menginisialisasi sebuah instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objectData | byte[] | Data objek yang disematkan. |
| ekstensi | java.lang.String | Ekstensi objek yang disematkan. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### OlePresentationOptions(String filePath, int pageNumber) {#OlePresentationOptions-java.lang.String-int-}
```
public OlePresentationOptions(String filePath, int pageNumber)
```


Menginisialisasi sebuah instance baru dari kelas [OlePresentationOptions](../../com.groupdocs.merger.domain.options/olepresentationoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### getX() {#getX--}
```
public final int getX()
```


Koordinat X dari bingkai objek tertanam.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public final void setX(int value)
```


Koordinat X dari bingkai objek tertanam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getY() {#getY--}
```
public final int getY()
```


Koordinat Y dari bingkai objek tertanam.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public final void setY(int value)
```


Koordinat Y dari bingkai objek tertanam.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar bingkai objek tersemat.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar bingkai objek tersemat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi bingkai objek tersemat.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi bingkai objek tersemat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

