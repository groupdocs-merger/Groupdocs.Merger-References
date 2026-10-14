---
title: "ImportDocumentOptions"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Menyediakan opsi untuk impor dokumen tersemat."
type: docs
weight: 14
url: /id/nodejs-java/com.groupdocs.merger.domain.options/importdocumentoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions)
```
public abstract class ImportDocumentOptions implements IImportDocumentOptions
```

Menyediakan opsi untuk impor dokumen tersemat.

--------------------

**Learn more**

 *  More about adding attachment to PDF documents: [How to add attachment to PDF document.][]
 *  More about adding document to Word processing via OLE: [Add document to Word processing via OLE.][]
 *  More about adding document to Presentation via OLE: [Add document to Presentation via OLE.][]
 *  More about adding document to Spreadsheet via OLE: [Add document to Spreadsheet via OLE.][]
 *  More about adding document to Diagram via OLE: [Add document to Diagram via OLE.][]


[How to add attachment to PDF document.]: https://docs.groupdocs.com/merger/java/how-to-add-attachment-to-pdf-document/
[Add document to Word processing via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-word-processing-via-ole/
[Add document to Presentation via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-presentation-via-ole/
[Add document to Spreadsheet via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-spreadsheet-via-ole/
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)](#ImportDocumentOptions-byte---java.lang.String-int-) | Menginisialisasi instance baru dari kelas [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
| [ImportDocumentOptions(String filePath, int pageNumber)](#ImportDocumentOptions-java.lang.String-int-) | Menginisialisasi instance baru dari kelas [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getObjectData()](#getObjectData--) | Data objek tersemat. |
| [getExtension()](#getExtension--) | Ekstensi objek tersemat. |
| [getPageNumber()](#getPageNumber--) | Nomor halaman untuk menyisipkan objek tersemat. |
| [getImageData(String filePath)](#getImageData-java.lang.String-) | Mendapatkan data gambar dari objek yang disematkan. |
### ImportDocumentOptions(byte[] objectData, String extension, int pageNumber) {#ImportDocumentOptions-byte---java.lang.String-int-}
```
public ImportDocumentOptions(byte[] objectData, String extension, int pageNumber)
```


Menginisialisasi instance baru dari kelas [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objectData | byte[] | Data objek tersemat. |
| ekstensi | java.lang.String | Ekstensi objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### ImportDocumentOptions(String filePath, int pageNumber) {#ImportDocumentOptions-java.lang.String-int-}
```
public ImportDocumentOptions(String filePath, int pageNumber)
```


Menginisialisasi instance baru dari kelas [ImportDocumentOptions](../../com.groupdocs.merger.domain.options/importdocumentoptions).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |
| pageNumber | int | Nomor halaman untuk menambahkan objek tersemat. |

### getObjectData() {#getObjectData--}
```
public final byte[] getObjectData()
```


Data objek tersemat.

**Returns:**
byte[]
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Ekstensi objek tersemat.

**Returns:**
java.lang.String
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Nomor halaman untuk menyisipkan objek tersemat.

**Returns:**
int
### getImageData(String filePath) {#getImageData-java.lang.String-}
```
public final byte[] getImageData(String filePath)
```


Mendapatkan data gambar dari objek yang disematkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari objek tersemat. |

**Returns:**
byte[]
