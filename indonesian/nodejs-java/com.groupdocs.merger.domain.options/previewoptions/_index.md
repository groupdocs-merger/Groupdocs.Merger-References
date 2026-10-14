---
title: "PreviewOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Mewakili opsi pratinjau dokumen."
type: docs
weight: 29
url: /id/nodejs-java/com.groupdocs.merger.domain.options/previewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.merger.domain.options.PageOptions](../../com.groupdocs.merger.domain.options/pageoptions)

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions)
```
public class PreviewOptions extends PageOptions implements IPreviewOptions
```

Mewakili opsi pratinjau dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-) | Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---) | Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-) | Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)](#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-) | Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Lebar pratinjau. |
| [setWidth(int value)](#setWidth-int-) | Lebar pratinjau. |
| [getHeight()](#getHeight--) | Tinggi pratinjau. |
| [setHeight(int value)](#setHeight-int-) | Tinggi pratinjau. |
| [getResolution()](#getResolution--) | Resolusi gambar. |
| [setResolution(int value)](#setResolution-int-) | Resolusi gambar. |
| [getMode()](#getMode--) | Mode untuk pratinjau. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Memvalidasi opsi pratinjau. |
| [getPathByPageNumber(int pageNumber, String extension)](#getPathByPageNumber-int-java.lang.String-) | Mendapatkan jalur lengkap file dokumen yang dipratinjau berdasarkan nomor halaman dengan ekstensi yang ditentukan. |
| [getPageStreamFactory()](#getPageStreamFactory--) | PageStreamFactory untuk membuat atau melepaskan aliran pratinjau halaman output. |
### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode)
```


Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| previewMode | int | Mode pratinjau dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int---}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int[] pageNumbers)
```


Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| previewMode | int | Mode pratinjau dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| pageNumbers | int[] | Nomor halaman. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber)
```


Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| previewMode | int | Mode pratinjau dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |

### PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode) {#PreviewOptions-com.groupdocs.merger.domain.common.PageStreamFactory-int-int-int-int-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int previewMode, int startNumber, int endNumber, int mode)
```


Menginisialisasi instance baru dari kelas [PreviewOptions](../../com.groupdocs.merger.domain.options/previewoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory) | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| previewMode | int | Mode pratinjau dari Mode (\#getMode.getMode/\#setMode(int).setMode(int)) |
| startNumber | int | Nomor halaman awal. |
| endNumber | int | Nomor halaman akhir. |
| mode | int | Mode rentang. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar pratinjau.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar pratinjau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi pratinjau.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi pratinjau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


Resolusi gambar.

**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Resolusi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getMode() {#getMode--}
```
public final int getMode()
```


Mode untuk pratinjau.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public final void validate(FileType fileType)
```


Memvalidasi opsi pratinjau.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Tipe berkas. |

### getPathByPageNumber(int pageNumber, String extension) {#getPathByPageNumber-int-java.lang.String-}
```
public final String getPathByPageNumber(int pageNumber, String extension)
```


Mendapatkan jalur lengkap file dokumen yang dipratinjau berdasarkan nomor halaman dengan ekstensi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | int | Nomor halaman pratinjau. |
| ekstensi | java.lang.String | Ekstensi file. |

**Returns:**
java.lang.String - Jalur file lengkap.
### getPageStreamFactory() {#getPageStreamFactory--}
```
public PageStreamFactory getPageStreamFactory()
```


PageStreamFactory untuk membuat atau melepaskan aliran pratinjau halaman output.

**Returns:**
[PageStreamFactory](../../com.groupdocs.merger.domain.common/pagestreamfactory)
