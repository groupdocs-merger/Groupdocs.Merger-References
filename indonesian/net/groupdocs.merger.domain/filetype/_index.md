---
title: "FileType"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Mewakili tipe file. Menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh GroupDocs.Merger, mendeteksi tipe file berdasarkan ekstensi, dll."
type: docs
weight: 110
url: /id/net/groupdocs.merger.domain/filetype/
---
## FileType class

Mewakili tipe file. Menyediakan metode untuk memperoleh daftar semua tipe file yang didukung oleh **GroupDocs.Merger**, mendeteksi tipe file berdasarkan ekstensi, dll.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Akhiran nama file (termasuk titik \".\") misalnya \".doc\". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Nama tipe file misalnya \"Microsoft Word Document\". |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Memetakan ekstensi file ke tipe file. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Menentukan apakah [`FileType`](../filetype) saat ini sama dengan objek [`FileType`](../filetype) yang ditentukan. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Menentukan apakah [`FileType`](../filetype) saat ini sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Mengembalikan kode hash untuk objek [`FileType`](../filetype) saat ini. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Mengambil tipe file yang didukung |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Menentukan apakah [`FileType`](../filetype) masukan berformat arsip. |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | Menentukan apakah [`FileType`](../filetype) masukan berformat audio. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Menentukan apakah [`FileType`](../filetype) masukan berformat gambar. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Menentukan apakah [`FileType`](../filetype) masukan berformat teks primitif. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Menentukan apakah dua objek [`FileType`](../filetype) sama. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Menentukan apakah dua objek [`FileType`](../filetype) tidak sama. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | File Gambar Bitmap (.bmp) mewakili file yang digunakan untuk menyimpan gambar digital bitmap. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | File Terkompresi Bzip2 (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | File Nilai Dipisahkan Koma (.csv) mewakili file teks biasa yang berisi catatan data dengan nilai yang dipisahkan koma. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/csv). |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Dokumen Microsoft Word (.doc) mewakili dokumen yang dihasilkan oleh Microsoft Word atau program pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | File Word Open XML Macro-Enabled Document (.docm) adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau yang lebih baru dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Microsoft Word Open XML Document (.docx) adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | File Word Document Template (.dot) adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Word Open XML Macro-Enabled Document Template (.dotm) merupakan file templat yang dibuat dengan Microsoft Word 2007 atau yang lebih baru. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) adalah file templat yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows Enhanced Metafile (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows Compressed Enhanced Metafile (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Open eBook File (.epub) adalah format file e-book yang menyediakan format publikasi digital standar bagi penerbit dan konsumen. Format ini kini sudah sangat umum sehingga didukung oleh banyak e-reader dan aplikasi perangkat lunak. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/ebook/epub). |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | Error Log File (.err) adalah file teks yang berisi pesan kesalahan yang dihasilkan oleh sebuah program. Pelajari lebih lanjut tentang format file ini [di sini](https://fileinfo.com/extension/err). |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | Graphical Interchange Format File (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | G-Zip Compressed File (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Hypertext Markup Language File (.html) adalah ekstensi untuk halaman web yang dibuat untuk ditampilkan di peramban. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/web/html). |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | JPEG Image (.jpeg) adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Gambar output, sebagai hasil kompresi, merupakan kompromi antara ukuran penyimpanan dan kualitas gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | JPEG Image (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | MHTML Web Archive (.mht) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/web/mhtml). |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | MIME HTML File (.mhtml) adalah format arsip halaman web yang dapat dibuat oleh sejumlah aplikasi berbeda. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/web/mhtml). |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | File dengan ekstensi .mp3 adalah format file yang terkode secara digital untuk file audio yang secara resmi didasarkan pada MPEG-1 Audio Layer III atau MPEG-2 Audio Layer III. Format ini dikembangkan oleh Moving Picture Experts Group (MPEG) yang menggunakan kompresi audio Layer 3. Kompresi yang dicapai oleh format file MP3 adalah 1/10 ukuran file .WAV atau .AIF. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/audio/mp3). |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | OpenDocument Presentation (.odp) merupakan format file presentasi yang digunakan oleh OpenOffice.org dalam standar OASISOpen. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | File OpenDocument Text Document (.odt) adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format OpenDocument Text File. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/odt). |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | File Dokumen OneNote (.one) dibuat oleh aplikasi Microsoft OneNote. OneNote memungkinkan Anda mengumpulkan informasi menggunakan aplikasi seolah-olah Anda menggunakan buku catatan draft untuk mencatat. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/note-taking/one). |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | Templat Presentasi OpenDocument (.otp) mewakili file templat presentasi yang dibuat oleh aplikasi dalam format standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/presentation/otp). |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | Templat Dokumen OpenDocument (.ott) mewakili dokumen templat yang dihasilkan oleh aplikasi yang mematuhi standar OpenDocument OASIS. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/ott). |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | File Portable Document Format (.pdf) adalah format file yang diperkenalkan sebagai standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/view/pdf). |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Portable Network Graphic (.png) adalah jenis format file gambar raster yang menggunakan kompresi lossless. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/png). |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | PowerPoint Slide Show (.pps) adalah file yang dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | PowerPoint Open XML Slide Show (.ppsx) adalah file yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | PowerPoint Presentation (.ppt) mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Binary File Format yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | PowerPoint Open XML Presentation (.pptx) adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang berbentuk biner, format PPTX berbasis pada format file presentasi open XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript File (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive Compressed File (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Rich Text Format File (.rtf) yang diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) mewakili metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/rtf). |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip Compressed File (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Scalable Vector Graphics File (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Scalable Vector Graphics Compressed File (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | Consolidated Unix File Archive (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | LaTeX Source Document (.tex) adalah bahasa yang mencakup fitur pemrograman serta penandaan, digunakan untuk menyusun dokumen. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/page-description-language/tex). |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | Tagged Image File (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Tagged Image File Format (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Tab Separated Values File (.tsv) mewakili data yang dipisahkan dengan tab dalam format teks biasa. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Plain Text File (.txt) mewakili dokumen teks yang berisi teks biasa dalam bentuk baris. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Mewakili tipe file yang tidak diketahui. |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Visio Drawing XML File (.vdx) adalah gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML dengan ekstensi .VDX. File XML gambar Visio dibuat dalam perangkat lunak Visio, yang dikembangkan oleh Microsoft. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | File Gambar Visio (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Visio Macro-Enabled Drawing (.vsdm) adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. File VSDM adalah gambar OPC/XML yang mirip dengan VSDX, tetapi juga menyediakan kemampuan untuk menjalankan makro saat file dibuka. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Visio Drawing (.vsdx) mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. Format ini dikembangkan untuk menggantikan format file biner, .VSD, yang didukung oleh versi Microsoft Visio sebelumnya. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | File Stencil Visio(.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Visio Macro-Enabled Stencil File (.vssm) adalah file Stencil Microsoft Visio yang mendukung makro. File VSSM ketika dibuka memungkinkan menjalankan makro untuk mencapai pemformatan dan penempatan bentuk yang diinginkan dalam diagram. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Visio Stencil File (.vssx) adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Format file VSSX dapat dibuka dengan Visio 2013 ke atas. File Visio dikenal karena representasi berbagai elemen gambar seperti kumpulan bentuk, konektor, diagram alur, tata letak jaringan, diagram UML. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Templat Gambar Visio (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Visio Macro-Enabled Drawing Template (.vstm) adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. Tidak seperti file VSDX, file yang dibuat dari templat VSTM dapat menjalankan makro yang dikembangkan dalam kode Visual Basic for Applications (VBA). Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Visio Drawing Template (.vstx) adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. File VSTX ini menyediakan titik awal untuk membuat gambar Visio, disimpan sebagai file .VSDX, dengan tata letak dan pengaturan default. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Visio Stencil XML File (.vsx) mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. File VSX disimpan dalam format file XML dan didukung hingga Visio 2013. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Visio Template XML File (.vtx) adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Templat ini bertujuan menyediakan file dengan pengaturan dasar yang dapat digunakan untuk membuat banyak file Visio dengan pengaturan yang sama. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | WAV, yang dikenal sebagai WAVE (Waveform Audio File Format), adalah subset dari spesifikasi Resource Interchange File Format (RIFF) milik Microsoft untuk menyimpan file audio digital. Format ini tidak menerapkan kompresi apa pun pada aliran bit dan menyimpan rekaman audio dengan berbagai laju sampel dan bitrate. Format ini telah menjadi dan tetap menjadi salah satu format standar untuk CD audio. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Add-In Excel yang Mendukung Makro (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Excel Spreadsheet (.xls) adalah file yang dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Excel Binary Spreadsheet (.xlsb) adalah format file yang menentukan Excel Binary File Format, yaitu kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) adalah jenis file Spreadsheet yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) adalah format yang terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) adalah file templat yang dibuat dengan Microsoft Excel, yang merupakan aplikasi spreadsheet yang termasuk dalam paket Microsoft Office. Microsoft Office 97-2003 mendukung pembuatan file XLT baru serta membuka file tersebut. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) mewakili file yang dihasilkan oleh Microsoft Excel sebagai file templat yang mendukung makro. File XLTM mirip dengan XLTX dalam struktur, kecuali bahwa yang terakhir tidak mendukung pembuatan file templat dengan makro. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | File Excel Open XML Spreadsheet Template (.xltx) didasarkan pada spesifikasi format file Office OpenXML. File ini digunakan untuk membuat file templat standar yang dapat digunakan untuk menghasilkan file XLSX yang memiliki pengaturan yang sama seperti yang ditentukan dalam file XLTX. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/spreadsheet/xltx). |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) mewakili file tata letak halaman yang didasarkan pada XML Paper Specifications yang dibuat oleh Microsoft. Pelajari lebih lanjut tentang format file ini [di sini](https://docs.fileformat.com/page-description-language/xps). |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | File Terkompresi (.zip) |

### Catatan

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Lihat Juga

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
