---
title: "Penggabung"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Mewakili kelas utama yang mengontrol proses penggabungan dokumen."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.merger/merger/
---
**Inheritance:**
java.lang.Object
```
public class Merger
```

Mewakili kelas utama yang mengontrol proses penggabungan dokumen.
## Constructors

| Constructor | Deskripsi |
| --- | --- |
| [Merger(InputStream document)](#Merger-java.io.InputStream-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath)](#Merger-java.lang.String-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
| [Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)](#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-) | Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [dispose()](#dispose--) | Membuang sumber daya. |
| [importDocument(IImportDocumentOptions importDocumentOptions)](#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-) | Mengimpor dokumen sebagai lampiran atau tertanam melalui Ole. |
| [join(InputStream document)](#join-java.io.InputStream-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(InputStream document, IJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(InputStream document, IPageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(InputStream document, ImageJoinOptions joinOptions)](#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(String filePath)](#join-java.lang.String-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(String filePath, IJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(String filePath, IPageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [join(String filePath, ImageJoinOptions joinOptions)](#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [createPageBuilder()](#createPageBuilder--) | Membuat Page builder baru dengan koleksi dokumen yang telah ditentukan. |
| [createPageBuilder(PageBuilderOptions pageBuilderOptions)](#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-) | Membuat Page builder baru dengan koleksi dokumen yang telah ditentukan. |
| [applyPageBuilder(PageBuilder pageBuilder)](#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-) | Menerapkan perubahan page builder. |
| [split(ISplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-) | Membagi dokumen tunggal menjadi beberapa dokumen. |
| [split(ITextSplitOptions splitOptions)](#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-) | Membagi dokumen tunggal menjadi beberapa dokumen. |
| [extractPages(IExtractOptions extractOptions)](#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-) | Membuat dokumen baru dengan beberapa halaman dari dokumen sumber. |
| [addPassword(IAddPasswordOptions addPasswordOptions)](#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-) | Melindungi dokumen dengan kata sandi. |
| [isPasswordSet()](#isPasswordSet--) | Memeriksa apakah dokumen dilindungi kata sandi. |
| [removePassword()](#removePassword--) | Menghapus kata sandi dari dokumen. |
| [updatePassword(IUpdatePasswordOptions updatePasswordOptions)](#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-) | Memperbarui kata sandi yang ada untuk dokumen. |
| [changeOrientation(IOrientationOptions orientationOptions)](#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-) | Menerapkan mode orientasi baru untuk halaman yang ditentukan. |
| [movePage(IMoveOptions moveOptions)](#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-) | Memindahkan halaman ke posisi baru dalam dokumen dengan format yang diketahui. |
| [removePages(IRemoveOptions removeOptions)](#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-) | Menghapus halaman dari dokumen dengan format yang diketahui. |
| [swapPages(ISwapOptions swapOptions)](#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-) | Menukar dua halaman dalam dokumen dengan format yang diketahui. |
| [rotatePages(IRotateOptions rotateOptions)](#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-) | Memutar halaman dokumen. |
| [getDocumentInfo()](#getDocumentInfo--) | Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum. |
| [generatePreview(IPreviewOptions previewOptions)](#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-) | Membuat pratinjau halaman dokumen. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Menyimpan dokumen hasil ke aliran document. |
| [save(String filePath)](#save-java.lang.String-) | Menyimpan file dokumen hasil ke filePath. |
| [save(String filePath, boolean useDefaultDirectory)](#save-java.lang.String-boolean-) | Menyimpan file dokumen hasil ke filePath. |
### Merger(InputStream document) {#Merger-java.io.InputStream-}
```
public Merger(InputStream document)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran yang dapat dibaca. |

### Merger(InputStream document, ILoadOptions loadOptions) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(InputStream document, ILoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran yang dapat dibaca. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Opsi pemuatan dokumen. |

### Merger(InputStream document, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, MergerSettings settings)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran yang dapat dibaca. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Pengaturan Penggabungan. |

### Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(InputStream document, ILoadOptions loadOptions, MergerSettings settings)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Aliran yang dapat dibaca. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Opsi pemuatan dokumen. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Pengaturan Penggabungan. |

### Merger(String filePath) {#Merger-java.lang.String-}
```
public Merger(String filePath)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file. |

### Merger(String filePath, ILoadOptions loadOptions) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-}
```
public Merger(String filePath, ILoadOptions loadOptions)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Opsi pemuatan dokumen. |

### Merger(String filePath, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, MergerSettings settings)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Pengaturan Penggabungan. |

### Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings) {#Merger-java.lang.String-com.groupdocs.merger.domain.options.interfaces.ILoadOptions-com.groupdocs.merger.MergerSettings-}
```
public Merger(String filePath, ILoadOptions loadOptions, MergerSettings settings)
```


Menginisialisasi instance baru dari kelas [Merger](../../com.groupdocs.merger/merger).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file. |
| loadOptions | [ILoadOptions](../../com.groupdocs.merger.domain.options.interfaces/iloadoptions) | Opsi pemuatan dokumen. |
| settings | [MergerSettings](../../com.groupdocs.merger/mergersettings) | Pengaturan Penggabungan. |

### dispose() {#dispose--}
```
public final void dispose()
```


Membuang sumber daya.

### importDocument(IImportDocumentOptions importDocumentOptions) {#importDocument-com.groupdocs.merger.domain.options.interfaces.IImportDocumentOptions-}
```
public final void importDocument(IImportDocumentOptions importDocumentOptions)
```


Mengimpor dokumen sebagai lampiran atau tertanam melalui Ole.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | importDocumentOptions | [IImportDocumentOptions](../../com.groupdocs.merger.domain.options.interfaces/iimportdocumentoptions) | Opsi impor dokumen tersemat. |

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
[Add document to Diagram via OLE.]: https://docs.groupdocs.com/merger/java/add-document-to-diagram-via-ole/ |

### join(InputStream document) {#join-java.io.InputStream-}
```
public final void join(InputStream document)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | dokumen | java.io.InputStream | Dokumen yang digabung. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(InputStream document, IJoinOptions joinOptions)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Dokumen yang digabung. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Opsi penggabungan. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(InputStream document, IPageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(InputStream document, IPageJoinOptions joinOptions)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Dokumen yang digabung. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Opsi penggabungan. |

--------------------

 **Learn more** 

 *   |

### join(InputStream document, ImageJoinOptions joinOptions) {#join-java.io.InputStream-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(InputStream document, ImageJoinOptions joinOptions)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.InputStream | Dokumen yang digabung. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | Opsi penggabungan gambar. |

--------------------

 **Learn more** 

 *   |

### join(String filePath) {#join-java.lang.String-}
```
public final void join(String filePath)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filePath | java.lang.String | Jalur file dari dokumen yang digabung. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IJoinOptions-}
```
public final void join(String filePath, IJoinOptions joinOptions)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari dokumen yang digabung. |
|  | joinOptions | [IJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ijoinoptions) | Opsi penggabungan. |

--------------------

**Learn more**

 *  More about document merge scenarios and use cases: [How to merge PDF, Word, Excel and PowerPoint documents in 3 steps][How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]


[How to merge PDF_ Word_ Excel and PowerPoint documents in 3 steps]: https://docs.groupdocs.com/merger/java/merge-files/ |

### join(String filePath, IPageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.interfaces.IPageJoinOptions-}
```
public final void join(String filePath, IPageJoinOptions joinOptions)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari dokumen yang digabung. |
|  | joinOptions | [IPageJoinOptions](../../com.groupdocs.merger.domain.options.interfaces/ipagejoinoptions) | Opsi penggabungan. |

--------------------

 **Learn more** 

 *   |

### join(String filePath, ImageJoinOptions joinOptions) {#join-java.lang.String-com.groupdocs.merger.domain.options.ImageJoinOptions-}
```
public final void join(String filePath, ImageJoinOptions joinOptions)
```


Menggabungkan dokumen menjadi satu dokumen tunggal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file dari dokumen yang digabung. |
|  | joinOptions | [ImageJoinOptions](../../com.groupdocs.merger.domain.options/imagejoinoptions) | Opsi penggabungan gambar. |

--------------------

 **Learn more** 

 *   |

### createPageBuilder() {#createPageBuilder--}
```
public final PageBuilder createPageBuilder()
```


Membuat Page builder baru dengan koleksi dokumen yang telah ditentukan.

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### createPageBuilder(PageBuilderOptions pageBuilderOptions) {#createPageBuilder-com.groupdocs.merger.domain.options.PageBuilderOptions-}
```
public final PageBuilder createPageBuilder(PageBuilderOptions pageBuilderOptions)
```


Membuat Page builder baru dengan koleksi dokumen yang telah ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageBuilderOptions | [PageBuilderOptions](../../com.groupdocs.merger.domain.options/pagebuilderoptions) |  |

**Returns:**
[PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) - The created page builder.
### applyPageBuilder(PageBuilder pageBuilder) {#applyPageBuilder-com.groupdocs.merger.domain.builders.PageBuilder-}
```
public final void applyPageBuilder(PageBuilder pageBuilder)
```


Menerapkan perubahan page builder.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageBuilder | [PageBuilder](../../com.groupdocs.merger.domain.builders/pagebuilder) | Pembuat halaman. |

### split(ISplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ISplitOptions-}
```
public final void split(ISplitOptions splitOptions)
```


Membagi dokumen tunggal menjadi beberapa dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | splitOptions | [ISplitOptions](../../com.groupdocs.merger.domain.options.interfaces/isplitoptions) | Opsi pemisahan halaman. |

--------------------

**Learn more**

 *  More about document split scenarios and use cases: [How to split PDF, Word, Excel and PowerPoint documents in 3 lines of code][How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]
 *  Quick guide about how to split text files in different ways: [Split text files guide][]


[How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]: https://docs.groupdocs.com/merger/java/split-document/
[Split text files guide]: https://docs.groupdocs.com/merger/java/split-text-file/ |

### split(ITextSplitOptions splitOptions) {#split-com.groupdocs.merger.domain.options.interfaces.ITextSplitOptions-}
```
public final void split(ITextSplitOptions splitOptions)
```


Membagi dokumen tunggal menjadi beberapa dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | splitOptions | [ITextSplitOptions](../../com.groupdocs.merger.domain.options.interfaces/itextsplitoptions) | Opsi pemisahan teks. |

--------------------

**Learn more**

 *  More about document split scenarios and use cases: [How to split PDF, Word, Excel and PowerPoint documents in 3 lines of code][How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]
 *  Quick guide about how to split text files in different ways: [Split text files guide][]


[How to split PDF_ Word_ Excel and PowerPoint documents in 3 lines of code]: https://docs.groupdocs.com/merger/java/split-document/
[Split text files guide]: https://docs.groupdocs.com/merger/java/split-text-file/ |

### extractPages(IExtractOptions extractOptions) {#extractPages-com.groupdocs.merger.domain.options.interfaces.IExtractOptions-}
```
public final void extractPages(IExtractOptions extractOptions)
```


Membuat dokumen baru dengan beberapa halaman dari dokumen sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | extractOptions | [IExtractOptions](../../com.groupdocs.merger.domain.options.interfaces/iextractoptions) | Opsi halaman. |

--------------------

**Learn more**

 *  More about how to extract specific document pages or page range: [How to extract pages from PDF, Word, Excel and PowerPoint documents][How to extract pages from PDF_ Word_ Excel and PowerPoint documents]


[How to extract pages from PDF_ Word_ Excel and PowerPoint documents]: https://docs.groupdocs.com/merger/java/extract-pages/ |

### addPassword(IAddPasswordOptions addPasswordOptions) {#addPassword-com.groupdocs.merger.domain.options.interfaces.IAddPasswordOptions-}
```
public final void addPassword(IAddPasswordOptions addPasswordOptions)
```


Melindungi dokumen dengan kata sandi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | addPasswordOptions | [IAddPasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iaddpasswordoptions) | Opsi untuk menentukan kata sandi. |

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/ |

### isPasswordSet() {#isPasswordSet--}
```
public final boolean isPasswordSet()
```


Memeriksa apakah dokumen dilindungi kata sandi.

**Returns:**
boolean - Mengembalikan nilai yang menunjukkan apakah dokumen dilindungi atau tidak.

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/
### removePassword() {#removePassword--}
```
public final void removePassword()
```


Menghapus kata sandi dari dokumen.

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/

### updatePassword(IUpdatePasswordOptions updatePasswordOptions) {#updatePassword-com.groupdocs.merger.domain.options.interfaces.IUpdatePasswordOptions-}
```
public final void updatePassword(IUpdatePasswordOptions updatePasswordOptions)
```


Memperbarui kata sandi yang ada untuk dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | updatePasswordOptions | [IUpdatePasswordOptions](../../com.groupdocs.merger.domain.options.interfaces/iupdatepasswordoptions) | Opsi untuk menentukan kata sandi saat ini/baru. |

--------------------

**Learn more**

 *  More about how to protect document with password: [How to protect PDF, Word, Excel and PowerPoint documents with password][How to protect PDF_ Word_ Excel and PowerPoint documents with password]
 *  More about how to update or change document password: [How to change document password][]
 *  More about how to check document password protected or not: [How to check document password protection][]
 *  More about how to remove document password: [How to remove PDF, Word, Excel and PowerPoint documents password][How to remove PDF_ Word_ Excel and PowerPoint documents password]


[How to protect PDF_ Word_ Excel and PowerPoint documents with password]: https://docs.groupdocs.com/merger/java/add-document-password/
[How to change document password]: https://docs.groupdocs.com/merger/java/update-document-password/
[How to check document password protection]: https://docs.groupdocs.com/merger/java/check-document-password-protection/
[How to remove PDF_ Word_ Excel and PowerPoint documents password]: https://docs.groupdocs.com/merger/java/remove-document-password/ |

### changeOrientation(IOrientationOptions orientationOptions) {#changeOrientation-com.groupdocs.merger.domain.options.interfaces.IOrientationOptions-}
```
public final void changeOrientation(IOrientationOptions orientationOptions)
```


Menerapkan mode orientasi baru untuk halaman yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | orientationOptions | [IOrientationOptions](../../com.groupdocs.merger.domain.options.interfaces/iorientationoptions) | Opsi perubahan orientasi. |

--------------------

**Learn more**

 *  More about how to change orientation for Microsoft Word document pages: [How to change Microsoft Word document pages orientation][]


[How to change Microsoft Word document pages orientation]: https://docs.groupdocs.com/merger/java/change-page-orientation/ |

### movePage(IMoveOptions moveOptions) {#movePage-com.groupdocs.merger.domain.options.interfaces.IMoveOptions-}
```
public final void movePage(IMoveOptions moveOptions)
```


Memindahkan halaman ke posisi baru dalam dokumen dengan format yang diketahui.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | moveOptions | [IMoveOptions](../../com.groupdocs.merger.domain.options.interfaces/imoveoptions) | Opsi pemindahan. |

--------------------

**Learn more**

 *  More about how to move page to another position within document: [How to move PDF, Word, Excel and PowerPoint document pages][How to move PDF_ Word_ Excel and PowerPoint document pages]


[How to move PDF_ Word_ Excel and PowerPoint document pages]: https://docs.groupdocs.com/merger/java/move-page/ |

### removePages(IRemoveOptions removeOptions) {#removePages-com.groupdocs.merger.domain.options.interfaces.IRemoveOptions-}
```
public final void removePages(IRemoveOptions removeOptions)
```


Menghapus halaman dari dokumen dengan format yang diketahui.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | removeOptions | [IRemoveOptions](../../com.groupdocs.merger.domain.options.interfaces/iremoveoptions) | Opsi untuk jumlah halaman yang akan dihapus. |

--------------------

**Learn more**

 *  More about how to remove page from document: [How to remove page from PDF, Word, Excel or PowerPoint document][How to remove page from PDF_ Word_ Excel or PowerPoint document]


[How to remove page from PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/remove-pages/ |

### swapPages(ISwapOptions swapOptions) {#swapPages-com.groupdocs.merger.domain.options.interfaces.ISwapOptions-}
```
public final void swapPages(ISwapOptions swapOptions)
```


Menukar dua halaman dalam dokumen dengan format yang diketahui.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | swapOptions | [ISwapOptions](../../com.groupdocs.merger.domain.options.interfaces/iswapoptions) | Opsi pertukaran. |

--------------------

**Learn more**

 *  More about how to swap pages positions within document: [How to swap pages inside PDF, Word, Excel or PowerPoint document][How to swap pages inside PDF_ Word_ Excel or PowerPoint document]


[How to swap pages inside PDF_ Word_ Excel or PowerPoint document]: https://docs.groupdocs.com/merger/java/swap-pages/ |

### rotatePages(IRotateOptions rotateOptions) {#rotatePages-com.groupdocs.merger.domain.options.interfaces.IRotateOptions-}
```
public final void rotatePages(IRotateOptions rotateOptions)
```


Memutar halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | rotateOptions | [IRotateOptions](../../com.groupdocs.merger.domain.options.interfaces/irotateoptions) | Opsi untuk memutar halaman. |

--------------------

**Learn more**

 *  More about how to rotate PDF document pages: [How to rotate PDF document pages][]


[How to rotate PDF document pages]: https://docs.groupdocs.com/merger/java/rotate-pages/ |

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum.

**Returns:**
[IDocumentInfo](../../com.groupdocs.merger.domain.result/idocumentinfo) - Information about document properties.

--------------------

**Learn more**

 *  Learn more about document file type, pages count, size and many other format specific properties: [How to get document info using GroupDocs.Merger][]


[How to get document info using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/get-document-information/
### generatePreview(IPreviewOptions previewOptions) {#generatePreview-com.groupdocs.merger.domain.options.interfaces.IPreviewOptions-}
```
public final void generatePreview(IPreviewOptions previewOptions)
```


Membuat pratinjau halaman dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | previewOptions | [IPreviewOptions](../../com.groupdocs.merger.domain.options.interfaces/ipreviewoptions) | Opsi pratinjau. |

--------------------

**Learn more**

 *  Learn more about how to generate previews for document pages: [How to generate document pages preview using GroupDocs.Merger][]


[How to generate document pages preview using GroupDocs.Merger]: https://docs.groupdocs.com/merger/java/generate-document-pages-preview/ |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Menyimpan dokumen hasil ke aliran document.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dokumen | java.io.OutputStream | Aliran dokumen. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Menyimpan file dokumen hasil ke filePath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Nama file atau jalur file lengkap. |

### save(String filePath, boolean useDefaultDirectory) {#save-java.lang.String-boolean-}
```
public final void save(String filePath, boolean useDefaultDirectory)
```


Menyimpan file dokumen hasil ke filePath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur file atau nama jika menggunakan direktori default. |
| useDefaultDirectory | boolean | Gunakan direktori default dari pengaturan. |

