---
title: "FileType"
second_title: "Referensi API GroupDocs.Merger untuk Node.js via Java"
description: "Mewakili tipe file."
type: docs
weight: 10
url: /id/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Mewakili tipe file. Menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh **GroupDocs.Merger**, mendeteksi tipe file berdasarkan ekstensi, dll.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Fields

| Field | Deskripsi |
| --- | --- |
| [Unknown](#Unknown) | Mewakili tipe file yang tidak diketahui. |
| [ZIP](#ZIP) | File Zip (.zip) |
| [SevenZ](#SevenZ) | File Kompresi 7-Zip (.7z) |
| [TAR](#TAR) | Arsip File Unix Terpadu (.tar) |
| [RAR](#RAR) | File Kompresi Roshal ARchive (.rar) |
| [VSSX](#VSSX) | File Stencil Visio (.vssx) adalah stencil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013 dan seterusnya. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) adalah file Stencil Microsoft Visio yang menyediakan dukungan untuk makro. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) mengacu pada stencil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) adalah gambar atau diagram yang dibuat di Microsoft Visio, namun disimpan dalam format XML dengan ekstensi .VDX. |
| [EPUB](#EPUB) | Open eBook File (.epub) adalah format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. |
| [BMP](#BMP) | Bitmap Image File (.bmp) mewakili file yang digunakan untuk menyimpan gambar digital bitmap. |
| [JPG](#JPG) | Gambar JPEG (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. |
| [PNG](#PNG) | Portable Network Graphic (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. |
| [PS](#PS) | File PostScript (.ps) |
| [TIF](#TIF) | File Tagged Image (.tif) |
| [TIFF](#TIFF) | Format File Tagged Image (.tiff) |
| [GIF](#GIF) | File Format Pertukaran Grafis (.gif) |
| [SVG](#SVG) | File Scalable Vector Graphics (.svg) |
| [SVGZ](#SVGZ) | File Scalable Vector Graphics Terkompresi (.svgz) |
| [EMF](#EMF) | Windows Enhanced Metafile (.emf) |
| [EMZ](#EMZ) | Windows Compressed Enhanced Metafile (.emz) |
| [HTML](#HTML) | Hypertext Markup Language File (.html) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. |
| [MHT](#MHT) | MHTML Web Archive (.mht) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. |
| [MHTML](#MHTML) | MIME HTML File (.mhtml) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. |
| [ONE](#ONE) | File OneNote Document (.one) dibuat oleh aplikasi Microsoft OneNote. |
| [PDF](#PDF) | Portable Document Format File (.pdf) adalah format file yang diperkenalkan sebagai standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. |
| [XPS](#XPS) | XML Paper Specification File (.xps) mewakili file tata letak halaman yang berbasis pada XML Paper Specifications yang dibuat oleh Microsoft. |
| [TEX](#TEX) | LaTeX Source Document (.tex) adalah bahasa yang mencakup fitur pemrograman serta penandaan, digunakan untuk menyusun dokumen. |
| [PPT](#PPT) | PowerPoint Presentation (.ppt) mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. |
| [PPTX](#PPTX) | PowerPoint Open XML Presentation (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. |
| [PPS](#PPS) | PowerPoint Slide Show (.pps) adalah file yang dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. |
| [PPSX](#PPSX) | PowerPoint Open XML Slide Show (.ppsx) adalah file yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. |
| [ODP](#ODP) | OpenDocument Presentation (.odp) mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASIS Open. |
| [OTP](#OTP) | OpenDocument Presentation Template (.otp) mewakili file templat presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument. |
| [XLS](#XLS) | Excel Spreadsheet (.xls) adalah file yang dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. |
| [XLSX](#XLSX) | Microsoft Excel Open XML Spreadsheet (.xlsx) adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft bersamaan dengan rilis Microsoft Office 2007. |
| [XLSM](#XLSM) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. |
| [XLSB](#XLSB) | Format file Excel Binary Spreadsheet (.xlsb) menentukan Excel Binary File Format, yang merupakan kumpulan catatan dan struktur yang menentukan isi buku kerja Excel. |
| [CSV](#CSV) | Comma Separated Values File (.csv) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. |
| [TSV](#TSV) | Tab Separated Values File (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods). |
| [XLTM](#XLTM) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) mewakili file yang dihasilkan oleh Microsoft Excel sebagai file templat yang mendukung makro. |
| [XLTX](#XLTX) | File Excel Open XML Spreadsheet Template (.xltx) didasarkan pada spesifikasi format file Office OpenXML. |
| [XLT](#XLT) | Excel Template File (.xlt) adalah file templat yang dibuat dengan Microsoft Excel, yang merupakan aplikasi spreadsheet yang termasuk dalam paket Microsoft Office. |
| [XLAM](#XLAM) | Add-In Excel yang Mendukung Makro (.xlam). |
| [DOC](#DOC) | Dokumen Microsoft Word (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau program pengolah kata lainnya dalam format file biner. |
| [DOCX](#DOCX) | Dokumen Microsoft Word Open XML (.docx) adalah format yang terkenal untuk dokumen Microsoft Word. |
| [DOCM](#DOCM) | File Dokumen Word Open XML yang Mendukung Makro (.docm) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. |
| [DOT](#DOT) | File Template Dokumen Word (.dot) adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOC atau DOCX selanjutnya. |
| [DOTX](#DOTX) | Template Dokumen Word Open XML (.dotx) adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOCX selanjutnya. |
| [DOTM](#DOTM) | Template Dokumen Word Open XML yang Mendukung Makro (.dotm) mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. |
| [RTF](#RTF) | File Rich Text Format (.rtf) yang diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) mewakili metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. |
| [TXT](#TXT) | File Teks Biasa (.txt) mewakili dokumen teks yang berisi teks polos dalam bentuk baris. |
| [ERR](#ERR) | File Log Kesalahan (.err) adalah file teks yang berisi pesan kesalahan yang dihasilkan oleh sebuah program. |
| [ODT](#ODT) | File Dokumen Teks OpenDocument (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format File Teks OpenDocument. |
| [OTT](#OTT) | Template Dokumen OpenDocument (.ott) mewakili dokumen templat yang dihasilkan oleh aplikasi sesuai dengan format standar OpenDocument OASIS. |
| [WAV](#WAV) | WAV, yang dikenal sebagai WAVE (Waveform Audio File Format), adalah subset dari spesifikasi Microsoft\u2019s Resource Interchange File Format (RIFF) untuk menyimpan file audio digital. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Nama tipe file, misalnya. |
| [getExtension()](#getExtension--) | Akhiran nama file (termasuk titik ".") misalnya. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Memetakan ekstensi file ke tipe file. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Mengambil tipe file yang didukung |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) saat ini sama dengan objek [FileType](../../com.groupdocs.merger.domain/filetype) yang ditentukan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) saat ini sama dengan objek yang ditentukan. |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk objek [FileType](../../com.groupdocs.merger.domain/filetype) saat ini. |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Menentukan apakah dua objek [FileType](../../com.groupdocs.merger.domain/filetype) sama. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Menentukan apakah dua objek [FileType](../../com.groupdocs.merger.domain/filetype) tidak sama. |
| [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) input adalah format teks primitif. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) input adalah format arsip. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) input adalah format teks primitif. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Menentukan apakah input [FileType](../../com.groupdocs.merger.domain/filetype) berformat audio. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Mewakili tipe file yang tidak diketahui.

### ZIP {#ZIP}
```
public static FileType ZIP
```


File Zip (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


File Kompresi 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Arsip File Unix Terpadu (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


File Kompresi Roshal ARchive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


File Stencil Visio (.vssx) adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal untuk representasi berbagai elemen gambar seperti kumpulan bentuk, konektor, diagram alur, tata letak jaringan, diagram UML, Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Visio Drawing (.vsdx) mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. Format ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Visio Macro-Enabled Drawing (.vsdm) adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Visio Drawing Template (.vstx) adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Visio Macro-Enabled Drawing Template (.vstm) adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari templat VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA). Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Visio Macro-Enabled Stencil File (.vssm) adalah file Stencil Microsoft Visio yang mendukung makro. File VSSM ketika dibuka memungkinkan menjalankan makro untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Visio Stencil XML File (.vsx) mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Visio Template XML File (.vtx) adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Templat ini bertujuan menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat banyak file Visio dengan pengaturan yang sama. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Visio Drawing XML File (.vdx) adalah gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML dengan ekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Open eBook File (.epub) adalah format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. Format ini kini sangat umum sehingga didukung oleh banyak pembaca e-book dan aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Bitmap Image File (.bmp) mewakili file yang digunakan untuk menyimpan gambar digital bitmap. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


Gambar JPEG (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


JPEG Image (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar output, sebagai hasil kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Portable Network Graphic (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


File PostScript (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


File Tagged Image (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Format File Tagged Image (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


File Format Pertukaran Grafis (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


File Scalable Vector Graphics (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


File Scalable Vector Graphics Terkompresi (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Windows Enhanced Metafile (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Windows Compressed Enhanced Metafile (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Hypertext Markup Language File (.html) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


MHTML Web Archive (.mht) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


MIME HTML File (.mhtml) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


File Dokumen OneNote (.one) dibuat oleh aplikasi Microsoft OneNote. OneNote memungkinkan Anda mengumpulkan informasi menggunakan aplikasi seolah-olah Anda menggunakan papan draf untuk mencatat. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


File Portable Document Format (.pdf) adalah format file yang diperkenalkan sebagai standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


File XML Paper Specification (.xps) mewakili file tata letak halaman yang berbasis pada XML Paper Specification yang dibuat oleh Microsoft. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


Dokumen Sumber LaTeX (.tex) adalah bahasa yang mencakup fitur pemrograman serta penanda, digunakan untuk menyusun dokumen. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Presentasi PowerPoint (.ppt) mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Binary File Format yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Presentasi PowerPoint Open XML (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang bersifat biner, format PPTX berbasis pada format file presentasi open XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Slide Show PowerPoint (.pps) adalah file yang dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Slide Show PowerPoint Open XML (.ppsx) adalah file yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Presentasi OpenDocument (.odp) mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASIS Open. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


Templat Presentasi OpenDocument (.otp) mewakili file templat presentasi yang dibuat oleh aplikasi dalam format standar OASIS OpenDocument. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Spreadsheet Excel (.xls) adalah file yang dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Spreadsheet Open XML Microsoft Excel (.xlsx) adalah format yang terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Spreadsheet Open XML Excel yang Mendukung Makro (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Format file Spreadsheet Biner Excel (.xlsb) menentukan Excel Binary File Format, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


File Nilai Dipisahkan Koma (.csv) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


File Nilai Dipisahkan Tab (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Templat Spreadsheet Open XML Excel yang Mendukung Makro (.xltm) mewakili file yang dihasilkan oleh Microsoft Excel sebagai file templat yang mendukung makro. File XLTM mirip dengan XLTX dalam struktur kecuali yang terakhir tidak mendukung pembuatan file templat dengan makro. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


File Templat Spreadsheet Open XML Excel (.xltx) didasarkan pada spesifikasi format file Office OpenXML. Ini digunakan untuk membuat file templat standar yang dapat digunakan untuk menghasilkan file XLSX yang memiliki pengaturan yang sama seperti yang ditentukan dalam file XLTX. Pelajari lebih lanjut tentang format file ini [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


File Template Excel (.xlt) adalah file templat yang dibuat dengan Microsoft Excel yang merupakan aplikasi spreadsheet yang merupakan bagian dari paket Microsoft Office. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membuka file tersebut. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Add-In Excel yang Mendukung Makro (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Dokumen Microsoft Word (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau program pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Dokumen Microsoft Word Open XML (.docx) adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


File Dokumen Word Open XML yang Mendukung Makro (.docm) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


File Template Dokumen Word (.dot) adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Template Dokumen Word Open XML (.dotx) adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Template Dokumen Word Open XML yang Mendukung Makro (.dotm) mewakili file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


File Rich Text Format (.rtf) yang diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) mewakili metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


File Teks Biasa (.txt) mewakili dokumen teks yang berisi teks polos dalam bentuk baris. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


File Log Kesalahan (.err) adalah file teks yang berisi pesan kesalahan yang dihasilkan oleh sebuah program. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


File Dokumen Teks OpenDocument (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format File Teks OpenDocument. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Template Dokumen OpenDocument (.ott) mewakili dokumen templat yang dihasilkan oleh aplikasi yang mematuhi format standar OpenDocument milik OASIS. Pelajari lebih lanjut tentang format file ini [di sini][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


WAV, yang dikenal sebagai WAVE (Waveform Audio File Format), adalah subset dari spesifikasi Resource Interchange File Format (RIFF) milik Microsoft untuk menyimpan file audio digital. Format ini tidak menerapkan kompresi apa pun pada aliran bit dan menyimpan rekaman audio dengan berbagai tingkat sampling dan bitrate. Format ini telah dan masih menjadi salah satu format standar untuk CD audio. Pelajari lebih lanjut tentang format file ini  [di sini][] .


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Nama tipe file misalnya "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Akhiran nama file (termasuk titik ".") misalnya ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Memetakan ekstensi file ke tipe file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ekstensi | java.lang.String | Ekstensi file (termasuk titik "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Mengambil tipe file yang didukung

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Mengembalikan urutan tipe file yang didukung
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) saat ini sama dengan objek [FileType](../../com.groupdocs.merger.domain/filetype) yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | Objek yang akan dibandingkan dengan objek [FileType](../../com.groupdocs.merger.domain/filetype) saat ini. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

if

```
obj
```

parameter adalah [FileType](../../com.groupdocs.merger.domain/filetype) dan sama dengan objek [FileType](../../com.groupdocs.merger.domain/filetype) saat ini; jika tidak,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk objek [FileType](../../com.groupdocs.merger.domain/filetype) saat ini.

**Returns:**
int - Kode hash untuk objek [FileType](../../com.groupdocs.merger.domain/filetype) saat ini.
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Menentukan apakah dua objek [FileType](../../com.groupdocs.merger.domain/filetype) sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Objek [FileType](../../com.groupdocs.merger.domain/filetype) kiri. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Objek [FileType](../../com.groupdocs.merger.domain/filetype) kanan. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### op_Inequality(FileType left, FileType right) {#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Inequality(FileType left, FileType right)
```


Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are not the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Left [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Right [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

jika kedua objek [FileType](../../com.groupdocs.merger.domain/filetype) tidak sama; sebaliknya,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.

**Returns:**
java.lang.String - Sebuah string yang merepresentasikan objek saat ini.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) input adalah format teks primitif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Objek [FileType](../../com.groupdocs.merger.domain/filetype). |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format; otherwise,

```
false
```
### isArchive(FileType fileType) {#isArchive-com.groupdocs.merger.domain.FileType-}
```
public static boolean isArchive(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is archive format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

jika input [FileType](../../com.groupdocs.merger.domain/filetype) berformat arsip; sebaliknya,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Menentukan apakah [FileType](../../com.groupdocs.merger.domain/filetype) input adalah format teks primitif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Objek [FileType](../../com.groupdocs.merger.domain/filetype). |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive image format; otherwise,

```
false
```
### isAudio(FileType fileType) {#isAudio-com.groupdocs.merger.domain.FileType-}
```
public static boolean isAudio(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is audio format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

jika input [FileType](../../com.groupdocs.merger.domain/filetype) berformat audio; sebaliknya,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
