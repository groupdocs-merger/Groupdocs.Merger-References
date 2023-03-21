---
title: FileType
second_title: GroupDocs.Merger untuk Referensi .NET API
description: Mewakili jenis file. Menyediakan metode untuk mendapatkan daftar semua jenis file yang didukung olehGroupDocs.Merger  mendeteksi tipe file dengan ekstensi etc.
type: docs
weight: 100
url: /id/net/groupdocs.merger.domain/filetype/
---
## FileType class

Mewakili jenis file. Menyediakan metode untuk mendapatkan daftar semua jenis file yang didukung oleh**GroupDocs.Merger** , mendeteksi tipe file dengan ekstensi etc.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Akhiran nama file (termasuk titik ".") misalnya ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nama jenis file misalnya "Dokumen Microsoft Word". |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Memetakan ekstensi file ke jenis file. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Menentukan apakah arus[`FileType`](../filetype) adalah sama dengan yang ditentukan[`FileType`](../filetype) objek. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Menentukan apakah arus[`FileType`](../filetype) sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Mengembalikan kode hash untuk saat ini[`FileType`](../filetype) objek. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Mengembalikan string yang mewakili objek saat ini. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Mengambil jenis file yang didukung |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Menentukan apakah masukan[`FileType`](../filetype) adalah format arsip. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Menentukan apakah masukan[`FileType`](../filetype) adalah format gambar. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Menentukan apakah masukan[`FileType`](../filetype) adalah format teks primitif. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Menentukan apakah dua[`FileType`](../filetype) objeknya sama. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Menentukan apakah dua[`FileType`](../filetype) objek tidak sama. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | File Gambar Bitmap (.bmp) merupakan file yang digunakan untuk menyimpan gambar digital bitmap. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | File Terkompresi Bzip2 (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | File Nilai yang Dipisahkan Koma (.csv) mewakili file teks biasa yang berisi rekaman data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word Document (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | File Word Open XML Macro-Enabled Document (.docm) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau lebih tinggi dengan kemampuan untuk menjalankan makro. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) adalah format terkenal untuk dokumen Microsoft Word. Diperkenalkan dari tahun 2007 dengan dirilisnya Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | File Word Document Template (.dot) adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) mewakili file template yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) adalah format file e-book yang menyediakan format publikasi digital standar untuk penerbit dan konsumen. Formatnya sudah sangat umum sekarang sehingga didukung oleh banyak aplikasi pembaca elektronik dan perangkat lunak. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | File Log Kesalahan (.err) adalah file teks yang berisi pesan kesalahan yang dihasilkan oleh suatu program. Pelajari lebih lanjut tentang format file ini[Di Sini](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | File Format Pertukaran Grafis (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | File Terkompresi G-Zip (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di browser. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | Gambar JPEG (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar keluaran, sebagai hasil kompresi, merupakan trade-off antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | Gambar JPEG (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) mewakili format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | File Dokumen Teks OpenDocument (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang didasarkan pada format File Teks OpenDocument. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | File OneNote Document (.one) dibuat oleh aplikasi Microsoft OneNote. OneNote memungkinkan Anda mengumpulkan informasi menggunakan aplikasi seolah-olah Anda menggunakan draftpad untuk membuat catatan. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | Template Presentasi OpenDocument (.otp) mewakili file template presentasi yang dibuat oleh aplikasi dalam format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | Templat Dokumen OpenDocument (.ott) mewakili dokumen templat yang dibuat oleh aplikasi sesuai dengan format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | File Format Dokumen Portabel (.pdf) adalah format file yang diperkenalkan sebagai standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang file ini format[Di Sini](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) adalah file yang dibuat menggunakan Microsoft PowerPoint untuk keperluan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) adalah file yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk keperluan Slide Show. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) merupakan file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Berbeda dengan versi sebelumnya dari format file presentasi PPT yang biner, format PPTX didasarkan pada format file presentasi terbuka XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | Berkas PostScript (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | File Terkompresi Roshal ARchive (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) mewakili metode pengkodean teks dan grafik yang diformat untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | File Terkompresi 7-Zip (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Arsip File Unix Terkonsolidasi (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | Dokumen Sumber LaTeX (.tex) adalah bahasa yang terdiri dari pemrograman serta fitur mark-up, yang digunakan untuk mengeset dokumen. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | File Gambar yang Ditandai (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Format File Gambar yang Ditandai (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | File Nilai Terpisah Tab (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) merupakan dokumen teks yang berisi teks biasa dalam bentuk garis. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Mewakili jenis file yang tidak diketahui. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) adalah gambar atau bagan yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML berekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Gambar Visio (.vsdx) mewakili format file Microsoft Visio yang diperkenalkan dari Microsoft Office 2013 dan seterusnya. Ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) adalah file Microsoft Visio Stencil yang mendukung menyediakan dukungan untuk makro. File VSSM saat dibuka memungkinkan menjalankan makro untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal untuk representasi berbagai elemen gambar seperti kumpulan bentuk, konektor, bagan alur, tata letak jaringan, diagram UML, Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) adalah file template yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari template VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA). Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) adalah file template gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | File XML Visio Stencil (.vsx) mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | File XML Template Visio (.vtx) adalah template gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Template ditujukan untuk menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat beberapa file Visio dengan pengaturan yang sama. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Add-In Berkemampuan Makro Excel (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) adalah file yang dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Format file Excel Binary Spreadsheet (.xlsb) menentukan Format File Biner Excel, yang merupakan kumpulan rekaman dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) adalah file template yang dibuat dengan Microsoft Excel yang merupakan aplikasi spreadsheet yang hadir sebagai bagian dari Microsoft Office suite. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membukanya. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) mewakili file yang dibuat oleh Microsoft Excel sebagai file template dengan Macro-enabled. File XLTM mirip dengan XLTX dalam struktur selain itu nanti tidak mendukung pembuatan file template dengan makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | File Excel Open XML Spreadsheet Template (.xltx) didasarkan pada spesifikasi format file Office OpenXML. Ini digunakan untuk membuat file template standar yang dapat digunakan untuk menghasilkan file XLSX yang menunjukkan pengaturan yang sama seperti yang ditentukan dalam file XLTX. Pelajari lebih lanjut tentang format file ini[Di Sini](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | File Spesifikasi Kertas XML (.xps) mewakili file tata letak halaman yang didasarkan pada Spesifikasi Kertas XML yang dibuat oleh Microsoft. Pelajari selengkapnya tentang format file ini[Di Sini](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | File ZIP (.zip) |

### Perkataan

**Belajarlah lagi**

* Pelajari lebih lanjut tentang format file yang didukung oleh GroupDocs.Merger: [Daftar lengkap format dokumen yang didukung](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Pelajari lebih lanjut tentang mendapatkan jenis file yang didukung dalam kode: [Cara mendapatkan format file yang didukung dalam kode](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Lihat juga

* ruang nama [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* perakitan [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
