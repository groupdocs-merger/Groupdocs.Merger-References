---
title: "Merger"
second_title: "Referensi API GroupDocs.Merger untuk .NET"
description: "Mewakili kelas utama yang mengontrol proses penggabungan dokumen."
type: docs
weight: 960
url: /id/net/groupdocs.merger/merger/
---
## Merger class

Mewakili kelas utama yang mengontrol proses penggabungan dokumen.

```csharp
public class Merger : IDisposable, IMerger
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_4)(Stream) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_8)(string) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_11)(string, MergerSettings) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Menginisialisasi instance baru dari kelas [`Merger`](../merger). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Melindungi dokumen dengan kata sandi. |
| [ApplyPageBuilder](../../groupdocs.merger/merger/applypagebuilder)(PageBuilder) | Menerapkan perubahan pembangun halaman. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Menerapkan mode orientasi baru untuk halaman yang ditentukan. |
| [CreatePageBuilder](../../groupdocs.merger/merger/createpagebuilder)(PageBuilderOptions) | Membuat Page builder baru dengan koleksi dokumen yang telah ditentukan. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Membuang sumber daya. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Membuat dokumen baru dengan beberapa halaman dari dokumen sumber. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Menghasilkan pratinjau halaman dokumen. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Mengimpor dokumen sebagai lampiran atau tertanam melalui Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Memeriksa apakah dokumen dilindungi kata sandi. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_3)(Stream, IPageJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IImageJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_6)(string, IJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_7)(string, IPageJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Memindahkan halaman ke posisi baru dalam dokumen dengan format yang diketahui. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Menghapus halaman dari dokumen dengan format yang diketahui. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Menghapus kata sandi dari dokumen. |
| [Rotate](../../groupdocs.merger/merger/rotate)(IRotateOptions) | Memutar gambar atau halaman dokumen. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream, ISaveOptions) | Menyimpan dokumen hasil ke aliran *document*. |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, ISaveOptions) | Menyimpan file dokumen hasil ke *filePath*. |
| [Save](../../groupdocs.merger/merger/save#save_1)(string, bool, ISaveOptions) | Menyimpan file dokumen hasil ke *filePath*. |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Membagi dokumen tunggal menjadi beberapa dokumen. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Membagi dokumen tunggal menjadi beberapa dokumen. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Menukar dua halaman dalam dokumen dengan format yang diketahui. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Memperbarui kata sandi yang ada untuk dokumen. |

### Lihat Juga

* interface [IMerger](../imerger)
* namespace [GroupDocs.Merger](../../groupdocs.merger)
* assembly [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.merger.dll -->
