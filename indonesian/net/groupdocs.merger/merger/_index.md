---
title: Merger
second_title: GroupDocs.Merger untuk Referensi .NET API
description: Mewakili kelas utama yang mengontrol proses penggabungan dokumen.
type: docs
weight: 790
url: /id/net/groupdocs.merger/merger/
---
## Merger class

Mewakili kelas utama yang mengontrol proses penggabungan dokumen.

```csharp
public class Merger : IDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Merger](merger#constructor)(Func&lt;Stream&gt;) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_4)(Stream) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_8)(string) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_1)(Func&lt;Stream&gt;, ILoadOptions) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_3)(Func&lt;Stream&gt;, MergerSettings) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_5)(Stream, ILoadOptions) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_7)(Stream, MergerSettings) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_9)(string, ILoadOptions) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_11)(string, MergerSettings) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_2)(Func&lt;Stream&gt;, ILoadOptions, MergerSettings) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_6)(Stream, ILoadOptions, MergerSettings) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |
| [Merger](merger#constructor_10)(string, ILoadOptions, MergerSettings) | Menginisialisasi instance baru[`Merger`](../merger) kelas. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [AddPassword](../../groupdocs.merger/merger/addpassword)(IAddPasswordOptions) | Melindungi dokumen dengan kata sandi. |
| [ChangeOrientation](../../groupdocs.merger/merger/changeorientation)(IOrientationOptions) | Menerapkan mode orientasi baru untuk halaman yang ditentukan. |
| [Dispose](../../groupdocs.merger/merger/dispose)() | Membuang sumber daya. |
| [ExtractPages](../../groupdocs.merger/merger/extractpages)(IExtractOptions) | Membuat dokumen baru dengan beberapa halaman dari dokumen sumber. |
| [GeneratePreview](../../groupdocs.merger/merger/generatepreview)(IPreviewOptions) | Menghasilkan pratinjau halaman dokumen. |
| [GetDocumentInfo](../../groupdocs.merger/merger/getdocumentinfo)() | Mendapat informasi tentang halaman dokumen: ukurannya, tinggi halaman maksimum, lebar halaman dengan tinggi maksimum. |
| [ImportDocument](../../groupdocs.merger/merger/importdocument)(IImportDocumentOptions) | Mengimpor dokumen sebagai lampiran atau disematkan melalui Ole. |
| [IsPasswordSet](../../groupdocs.merger/merger/ispasswordset)() | Memeriksa apakah dokumen dilindungi kata sandi. |
| [Join](../../groupdocs.merger/merger/join#join)(Stream) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_3)(string) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_1)(Stream, IImageJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_2)(Stream, IJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_4)(string, IImageJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [Join](../../groupdocs.merger/merger/join#join_5)(string, IJoinOptions) | Menggabungkan dokumen menjadi satu dokumen tunggal. |
| [MovePage](../../groupdocs.merger/merger/movepage)(IMoveOptions) | Memindahkan halaman ke posisi baru dalam dokumen dengan format yang diketahui. |
| [RemovePages](../../groupdocs.merger/merger/removepages)(IRemoveOptions) | Menghapus halaman dari dokumen dengan format yang diketahui. |
| [RemovePassword](../../groupdocs.merger/merger/removepassword)() | Menghapus kata sandi dari dokumen. |
| [RotatePages](../../groupdocs.merger/merger/rotatepages)(IRotateOptions) | Putar halaman dokumen. |
| [Save](../../groupdocs.merger/merger/save#save)(Stream) | Menyimpan dokumen hasil ke aliran*document* . |
| [Save](../../groupdocs.merger/merger/save#save_1)(string) | Menyimpan file dokumen hasil ke*filePath* . |
| [Save](../../groupdocs.merger/merger/save#save_2)(string, bool) | Menyimpan file dokumen hasil ke*filePath* . |
| [Split](../../groupdocs.merger/merger/split#split)(ISplitOptions) | Membagi satu dokumen menjadi beberapa dokumen. |
| [Split](../../groupdocs.merger/merger/split#split_1)(ITextSplitOptions) | Membagi satu dokumen menjadi beberapa dokumen. |
| [SwapPages](../../groupdocs.merger/merger/swappages)(ISwapOptions) | Menukar dua halaman dalam dokumen dengan format yang diketahui. |
| [UpdatePassword](../../groupdocs.merger/merger/updatepassword)(IUpdatePasswordOptions) | Memperbarui kata sandi yang ada untuk dokumen. |

### Lihat juga

* ruang nama [GroupDocs.Merger](../../groupdocs.merger)
* perakitan [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
